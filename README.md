# function-task-2
def smart_calculator(*args,operation):
    if operation =="sum":
        result = sum(args)
        return result 
    elif operation == "multiply":
        result = 1
        for num in args:
            result = result * num
        return result 

respond = smart_calculator(2,3,4,operation = "sum")
print(f"jodne par tumhara answer ye aya {respond}")
 
respond2 = smart_calculator(2,3,4,operation = "multiply")
print(f"gunna krne par tumhara answer ye aya{respond2}")
