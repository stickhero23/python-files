
import os
import pandas as pd
import csv

pwd = os.getcwd()

dataset = pd.read_csv(pwd + "\\2012_SAT_Results.csv")
# print(dataset)

dataset_modified = dataset.copy()

df = pd.DataFrame(dataset_modified, columns=['DBN', 'SCHOOL NAME', 'Num of SAT Test Takers', 'SAT Critical Reading Avg. Score', 'SAT Math Avg. Score', 'SAT Writing Avg. Score'])
contains_k = df[df['DBN'].str.contains('K')]
print("Average Score in borough K")
print(contains_k)

sum_of_k = sum(contains_k['SAT Math Avg. Score'].astype(int))
count_of_k = len(contains_k)

average_k = sum_of_k / count_of_k

print("The sum of Math average score in Borough K")
print(sum_of_k)
print("Number of rows of Borough K ")
print(count_of_k)
print("Average of Borough K ")
print(average_k)

print("")
print("")
print("***********************************************")

contains_x = df[df['DBN'].str.contains('X')]
print("Average Score in borough X")
print(contains_x)


sum_of_x = sum(contains_x['SAT Math Avg. Score'].astype(int))
count_of_x = len(contains_x)

average_x = sum_of_x / count_of_x

print("The sum of Math average score in Borough X")
print(sum_of_x)
print("Number of rows of Borough X ")
print(count_of_x)
print("Average of Borough X ")
print(average_x)

print("")
print("")
print("***********************************************")

contains_q = df[df['DBN'].str.contains('Q')]
print("Average Score in borough Q")
print(contains_q)

sum_of_q = sum(contains_q['SAT Math Avg. Score'].astype(int))
count_of_q = len(contains_q)

average_q = sum_of_q / count_of_q

print("The sum of Math average score in Borough Q")
print(sum_of_q)
print("Number of rows of Borough Q ")
print(count_of_q)
print("Average of Borough Q ")
print(average_q)

print("")
print("")
print("***********************************************")


contains_m = df[df['DBN'].str.contains('M')]
print("Average Score in borough M")
print(contains_m)
sum_of_m = sum(contains_m['SAT Math Avg. Score'].astype(int))
count_of_m = len(contains_m)

average_m = sum_of_m / count_of_m

print("The sum of Math average score in Borough M")
print(sum_of_m)
print("Number of rows of Borough R ")
print(count_of_m)
print("Average of Borough M ")
print(average_m)

print("")
print("")
print("***********************************************")

contains_r = df[df['DBN'].str.contains('R')]
print("Average Score in borough R")
print(contains_m)

sum_of_r = sum(contains_r['SAT Math Avg. Score'].astype(int))
count_of_r = len(contains_r)

average_r = sum_of_r / count_of_r

print("The sum of Math average score in Borough R")
print(sum_of_r)
print("Number of rows of Borough R ")
print(count_of_r)
print("Average of Borough R ")
print(average_r)

# print(dataset_modified[dataset_modified["DBN"]=='01M292'])

# print(dataset_modified.columns)

column = dataset_modified["DBN"]
# print(dataset_modified["DBN"].str.extract("(?P<District>.{2})(?P<Borough>.{1})(?P<School>.*)"))

# print(column.str.extract("?P<District_Num>.{2})(?P<District>.*)"))
added_columns = dataset_modified["DBN"].str.extract("(?P<District>.{2})(?P<Borough>.{1})(?P<School>.*)")
p = added_columns['District'], added_columns['Borough'], added_columns['School']



# print(added_columns.rows)


# f = open('sat_added.csv', 'w', encoding='UTF8', newline='')

# writer = csv.writer(f)
# writer.writerow(added_columns)
# writer.writerows(p)

# print(p)

# f.close()

