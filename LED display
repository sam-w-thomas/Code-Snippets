one = [[0, 0, 1], [0, 0, 1], [0,0,1], [0,0,1], [0,0,1]]
two = [[1, 1, 1], [0, 0, 1], [1,1,1], [1,0,0], [1,1,1]]
three = [[1, 1, 1], [0, 0, 1], [1,1,1], [0,0,1], [1,1,1]]
four = [[1, 0, 1], [1, 0, 1], [1,1,1], [0,0,1], [0,0,1]]
five = [[1, 1, 1], [1, 0, 0], [1,1,1], [0,0,1], [1,1,1]]
six = [[1, 1, 1], [1, 0, 0], [1,1,1], [1,0,1], [1,1,1]]
seven = [[1, 1, 1], [0, 0, 1], [0,0,1], [0,0,1], [0,0,1]]
eight = [[1, 1, 1], [1, 0, 1], [1,1,1], [1,0,1], [1,1,1]]
nine = [[1, 1, 1], [0, 0, 1], [0,0,1], [0,0,1], [0,0,1]]
zero = [[1, 1, 1], [1, 0, 1], [1,0,1], [1,0,1], [1,1,1]]

digit_letter = {1: one, 2:two, 3:three, 4:four, 5:five, 6:six, 7:seven, 8:eight, 9:nine, 0:zero}

numbers = input("Please input a number > ")

length = len(str(numbers))

for height in range(0, 5):
    for i in range(0, length):
        digit = digit_letter[int(numbers[i])][height]
        for value in digit:
            if value == 0:
                print(" ", end="")
            else:
                print("#", end="")

        print(" ", end="")
    print()
