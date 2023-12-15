# Python-4
# Problem 4: Concert Tickets

# Get user input for number of concert tickets
quantity = int(input("Enter the number of concert tickets: "))

# Determine the price per ticket based on the volume
if quantity >= 25:
    price_per_ticket = 50
elif 10 <= quantity <= 24:
    price_per_ticket = 60
elif 5 <= quantity <= 9:
    price_per_ticket = 70
else:
    price_per_ticket = 75

# Calculate total cost
total_cost = quantity * price_per_ticket

# Display results
print(f"\nNumber of Tickets: {quantity}")
print(f"Price Per Ticket: ${price_per_ticket}")
print(f"Total Cost: ${total_cost}")
