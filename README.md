# ice-cream
class IceCream:
    def __init__(self, flavor, topping, price):
        self.flavor = flavor
        self.topping = topping
        self.price = price

    def display_info(self):
        print(f"Ice Cream: {self.flavor}")
        print(f"Topping: {self.topping}")
        print(f"Price: ${self.price}")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the IceCream class
    my_ice_cream = IceCream(flavor="Vanilla", topping="Sprinkles", price=3.50)

    # Displaying information about the ice cream
    my_ice_cream.display_info()
