# caminar-en-el-mundo
print("Hola soy reeborg")
print("voy para una mision")

'''
Descrpción: Es una caminata para un mundo de cinco por cinco
Autor:william gutierrez
fecha: 29-07-2019


funcionalidad:
pre: Reeborg esta en(1,1) y reeborg camina hacia el norte
pos: reeborg está en (5,1) || reeborg esta en (1,5) 
'''
'''
def walk():
    if front_is_clear():
        repeat 4:
            move()
walk()
'''
def sic():
    repeat 4:
      move()
      repeat 3:
            turn_left()
      move()
      turn_left()
        
               
sic()
'''
Descrpción:
Autor:
fecha:


funcionalidad:
pre: Reeborg esta en(1,1) y reeborg camina hacia el norte
pos: reeborg está en (5,5) y 
'''
