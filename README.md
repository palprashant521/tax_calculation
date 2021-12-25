# tax_calculation
To simply calculate the tax and return the cost, tax rate and amount.

def tax(tax_rate, cost):
    
    amount = cost + cost*tax_rate/100
    
    print("The cost of the product is: {}".format(cost))
    print('\n')
    print("The tax rate applicable on the product is: {}".format(tax_rate))
    print('\n')
    print("The total amount after taxes is: {}".format(amount))
    
    tax(17,1000)
