# Ascending-order.ipy
The numbers which are appear in the ascending order from the given list# Define a ascending order list
my_list = [87,98,5,70,34,44,14,65,168,0,56]

# Initialize an empty list to store the sorted elements
sorted_list = []

# Make a copy of the original list
temp_list = my_list.copy()

#Iterate over the original list
for i in range(len(my_list)):
    # Find the minimum value in the temporary list
    min_val = min(temp_list)
    
    # Append the minimum value to the sorted list
    sorted_list.append(min_val)
    
    # Remove the minimum value from the temporary list
    temp_list.remove(min_val)

# Print the sorted list
print(sorted_list)
