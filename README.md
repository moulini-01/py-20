# py-20
printing all capital letters
def count_upper(s):
    count=0
    for i in s:
        if (i.isupper()):
            count+=1
    return count
print(count_upper("HkLLO"))
