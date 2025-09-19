import math

#average
print("请输入您要求的平均值")
total = 0
count = 0
user_input = input("请输入数字（完成所有数字输入后，请按=终止程序）")
while user_input != "=":
    num = float(user_input)
    total += num
    count += 1
    user_input = input("请输入数字（完成所有数字输入后，请按=终止程序）")
if count == 0:
    result ==0
else:
    result = math.floor(total / count)
print("您输入的平均值为:"+str(result))






