n = int(input('число n = '))
nums_cube_gen = (num for num in range(1, n + 1, 2))
nums_cube = list(nums_cube_gen)
print(*nums_cube)
