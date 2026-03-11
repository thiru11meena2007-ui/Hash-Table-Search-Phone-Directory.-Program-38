# Hash-Table-Search-Phone-Directory.-Program-38

phone_book = {"Alice":"123-456","Bob":"234-567","Charlie":"345-678"}
name = "Bob"

number = phone_book.get(name, None)
print(f"{name}'s number is {number}" if number else f"{name} not found")


Bob's number is 234-567
