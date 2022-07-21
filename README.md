# import random

n = random.randint(1, 30)
a = 0
while True:
    x = input("맞춰봐 ")
    g = int(x)
    if g == n:
        print("정답", a + 1, "번째에 맞춤")
        break
    if g < n:
        print("큼")
        a = a + 1
    if g > n:
        print("작음")
        a = a + 1
