













































�ndice
C�digos 
# �Qu� es python?
# Hola mundo ------------------------ ----------------------------------------------------------1
# �rea de la habitaci�n ------------- ---------------------------------------------------------2
# �rea de la cancha en acres --------------------------------------------------------------3
# precio de botellas ---------------------------------------------------------------------------4
# Conversi�n de unidades mexicanas ---------------------------------------------------5
# Direcci�n-------------------------------------------------------------------------------------- 6
# N�meros enteros ----------------------------------------------------------------------------7
# Restaurante -----------------------------------------------------------------------------------8
# Despliegue de n�meros enteros ---------------------------------------------------------9
# widgates----------------------------------------------------------------------------------------10
# Gasolina ----------------------------------------------------------------------------------------11
# ahorro -------------------------------------------------------------------------------------------12
# Resultado de d�as ----------------------------------------------------------------------------13
# Edad humana a edad perros---------------------------------------------------------------14
# Numero par e impar --------------------------------------------------------------------------15
# import time --------------------------------------------------------------------------------------16
# import math ----------------------------------------------------------------------------------------
# � Qu� es ? ------------------------------------------------------------------------------------------
# Latitud de la tierra en kil�metros------------------------------------------------------------17
# Radio de la esfera------------------------------------------------------------------------------18




#  Posici�n de cuadro de ajedrez----------------------------------------------------19 
# Estatura-----------------------------------------------------------------------------------20
# Metros equivalentes -------------------------------------------------------------------21
# �rea del triangulo  ----------------------------------------------------------------------22
# Distancia recorrida----------------------------------------------------------------------23
# Descuento---------------------------------------------------------------------------------24
#  Suma---------------------------------------------------------------------------------------25
# Grafica--------------------------------------------------------------------------------------26
# password-----------------------------------------------------------------------------------27
# C�lculo del �ndice de masa corporal ------------------------------------------------28
# signo zodiacal------------------------------------------------------------------------------29
# Grados-----------------------------------------------------------------------------------------30
# Ejercicios librer�a class---------------------------------------------------------------------
# Ma�anitas ------------------------------------------------------------------------------------31
# Gasolina --------------------------------------------------------------------------------------32
# �ngulos-----------------------------------------------------------------------------------------33
# Gr�ficos-----------------------------------------------------------------------------------------
# Pol�gono-----------------------------------------------------------------------------------------34
#gato-----------------------------------------------------------------------------------------35
# Gatos-----------------------------------------------------------------------------------------36
# Espiral-----------------------------------------------------------------------------------------37




# Tortugas en x----------------------------------------------------------------------------------38
# C�rculos -----------------------------------------------------------------------------------------39
# Cuadros -----------------------------------------------------------------------------------------40
# senoidal -----------------------------------------------------------------------------------------41
# Circulo con cuadros --------------------------------------------------------------------------42
# Cuadros  -----------------------------------------------------------------------------------------43
# Arco -----------------------------------------------------------------------------------------44
















# python anaconda
# �Que es python?
python es un Lenguaje de programaci�n de prop�sito general, orientado a objetos, que tambi�n puede utilizarse para el desarrollo web. En python hay diferentes tipos de programas como spyder,anaconda prompt los cuales se puedes usar para el lenguaje de programaci�n python .
C�digos:


. C�digo 1# Hola mundo
En este c�digo el sistema le preguntara al usuario que inserte su nombre y el sistema le va a imprimir un saludo al usuario.
C�digo                                                                                                                   


  
  # print('inserta tu nombre')
   nombre = imput()
   print('hola' + nombre)




Codigo2  # �rea de una habitaci�n
En este c�digo el equipo le va pregunta al usuario que inserte el ancho y el largo de la habitaci�n y el equipo va a imprimir el �rea de la habitaci�n. 


largo = float(input('insertar el largo de la habitacion: '))
ancho = float(input('insertar el ancho de tu habitacion: '))
area = largo * ancho 
print('el area de tu habitacion es' ,area, 'metros cuadrados')
 


C�digo 3: # �rea de la cancha en acres.
En este c�digo el equipo le va a preguntar al usuario que inserte el ancho y el largo de la cancha y el equipo va a imprimir el �rea de la cancha en acres.

 
# -*- coding: utf-8 -*-
print('hola usuario que vas a medir')
respuesta=input()
largo=float(input('cuanto mide el largo del campo de futbol: '))
ancho=float(input('cuanto mide el ancho del campo de futbol: '))
area=largo * ancho
area2=area * 90.70
area3=area2 / 43560
print('el area del campo de futbol es' ,area, 'metros cuadrados')
print('el area del campo de futbol es' ,area2, 'en pies cuadrados')
print('el area del campo de futbol es' , area3, 'en acres')


  
 C�digo 4: # precio de botellas 
 En este c�digo en equipo le va a preguntar al usuario que inserte botellas de a 1 litro y que inserte botellas de m�s de un litro  y el equipo va imprimir el precio por botella y cu�nto dinero es el que se le va dar al cliente.

 botella1=int(input('cuantas botellas de 1 litro o menos traes: '))
botella2=float(input('cuantas botellas de 1 litro o mas traes: '))
total=botella1 + botella2
print('tienes un total de' ,total, 'botellas')
precio1=botella1 * 1
print('el precio de botellas de menos de 1 litro es ',precio1,'pesos')
precio2=botella2 * 2.50
print('el precio de botellas de mas de 1 litro es ',precio2,'pesos')
precio= precio1 + precio2
print('el precio total es' ,precio,'pesos')


C�digo 5: # conversi�n de unidades mexicanas
en este c�digo en equipo realizara una conversi�n de n�meros PNG a kil�metros el usuario tiene que ingresar los n�meros PGN y el equipo va realizar la conversi�n a kil�metros.

 
milla=float(input('ingresa el numero de MPG:'))
conversion=235.215/milla 
print('la conversion a unidades mexicanas es:',conversion,'L/100km')



C�digo 6:# direcci�n  
En este c�digo se har� un destinatario de una carta para que llegue a su domicilio 

# Ejercicio 6. Direccion de correo
# Alumno: jesus morales
# Fecha: 12/03/19

nombre ='jesus morales carandia'
calle ='Chalchihuites 23'
colonia = 'San Jose de los Leones'
municipio = 'Naucalpan de Juarez'
estado = 'Estado de Mexico'
codigo_postal = 53760

print(nombre)\n
print(calle)\n
print(colonia)\n
print(municipio)\n
print(estado)\n
print(codigo_postal)\n

 
C�digo 7: # n�meros enteros
En este c�digo el equipo va desplegar dos mensajes uno que va decir que ingrese un numero entero y el otro que inserte otro n�mero entero y el equipo  va a imprimir multiplicaci�n,resta,divisi�n,modulo,exponente,etc

 a=int(input('Ingrese un numero entero'))
b=int(input('Ingrese un segundo numero entero'))
import math
suma=a+b
resta=b-a
multi=a*b
modulo=a%b
division=a/b
exponente= a**b

print('la suma es:',suma,)
print('la resta es:',resta,)
print('el producto es:',multi,)
print('El cociente es:',modulo,)
print('El residuo es:',division,)
print('El resultado de elevar a por b:',exponente,)
print('el logaritmo de 10 de a es:',math.log(a))


C�digo 8: # restaurante 
En este c�digo en equipo va desplegar un mensaje que el cliente va a  insertar el precio de la comida y el equipo va realizar un cobro donde le va decir al cliente  cuanto debe de pagar con todo y propina.  


restaurante = "HUSH"
direccion = "Chalchihuites 23 San Jose de Los Leones"
comida =float(input('ingrese precio de la comida: '))
impuesto = comida/100*16
propina = comida/100*10
r = comida + propina + impuesto
print(restaurante)
print(direccion)
print(comida)
print(impuesto)
print(propina)
print('$' , r , 'MXN' )
 

C�digo 9: # despliegue de n�meros enteros
En este c�digo en equipo va desplegar un mensaje que el usuario debe de insertar un numero entero y positivo donde en equipo va a imprimir la suma de los n�meros y te dir� que suma es.

 print('DESPLIEGUE DE SUMA DE NUMEROS ENTEROS')
numero = float(input('inserte un numero entero y positivo: '))
n= numero + 1
n2= numero + 2
n3= numero + 3
n4= numero + 4
n5= numero + 5
n6= numero + 6
n7= numero + 7
n8= numero + 8
n9= numero + 9
n10= numero + 10
suma = n * n + 1
suma2= n2 * n2 + 1  
suma3= n3 * n3 + 1 
suma4= n4 * n4 + 1 
suma5= n5 * n5 + 1 
suma6= n6 * n6 + 1 
suma7= n7 * n7 + 1 
suma8= n8 * n8 + 1 
suma9= n9 * n9 + 1 
suma10= n10 * n10 + 1
print('la suma de numeros es' ,suma,)
print('la suma de numeros es' ,suma2,)
print('la suma de numeros es' ,suma3,)
print('la suma de numeros es' ,suma4,)
print('la suma de numeros es' ,suma5,)
print('la suma de numeros es' ,suma6,)
print('la suma de numeros es' ,suma7,)
print('la suma de numeros es' ,suma8,)
print('la suma de numeros es' ,suma9,)
print('la suma de numeros es' ,suma10,)




C�digo 10: # widgates 
En este c�digo el equipo va desplegar un mensaje que dice cu�ntos gizmos llevas y el equipo va calcular cu�ntos productos llevas y los va a calcular por su precio y el equipo va desplegar un mensaje dici�ndote cuanto debes de los productos seleccionados.

 widgate1=int(input('cuantos widgates llevas: '))
gizmo1=float(input('cuantos gizmos llevas: '))
total=widgate1 + gizmo1
print('llevas un total de' ,total, 'productos en tu pedido')
peso1=widgate1 * 75
print('el peso de tus widgates es de ',peso1,'gramos')
peso2=gizmo1 * 112
print('el peso de tus gizmos es de ' ,peso2,'gramos')
peso= peso1 + peso2
print('el peso total de tu pedido es' ,peso,'gramos')

C�digo 11: # gasolina 
En este c�digo en equipo va desplegar un mensaje diciendo que el cliente inserte la cantidad de eficiencia de gasolina y en equipo va a imprimir la eficiencia en 100km para cuantos kil�metros le alcanza. 


numero=float(input('ingrese la cantidad de eficiencia de gasolina: '))
eficiencia=235.215/numero
print('la eficiencia de gasolina en L/100km es: ',eficiencia,) 



C�digo 12: # ahorro 
En este c�digo en equipo va desplegar un mensaje diciendo que ingrese la cantidad que quiere ahorrar y el equipo va realizar la evaluaci�n de la cantidad que se ahorr� la persona.

print('Cuenta de ahorro')
ahorro = float(input('ingrese la cantidad que se ahorra: '))
interes= ahorro/100*4.22
interes2= ahorro/100*8.34
interes3= ahorro/100*12.59
total= ahorro + interes
total2= ahorro + interes2
total3= ahorro + interes3
print('la cantidad que se ahorra es','$' ,total, 'MXN')
print('la cantidad que se ahorra es','$' ,total2, 'MXN')
print('la cantidad que se ahorra es','$' ,total3, 'MXN')



C�digo 13: # resultado de d�as 
En este c�digo en equipo va desplegar un mensaje dici�ndole al usuario que inserte n�mero de horas, minutos y segundos que desea saber el usuario y el equipo va a imprimir  la hora y los segundos  que el usuario debe saber.

 
dias=float(input('inserta el numero de dias: '))
d=dias
horas=float(input('inserta el numero de horas: '))
h=horas
minutos=float(input('inserta el numero de minutos: '))
m=minutos
segundos=float(input('inserta el numero de segundos: '))
s=segundos
resultado=d * 86400
resultado2= h * 3600
resultado3= m * 60
resultado4= s * 1
resultado5= resultado + resultado2 + resultado3 + resultado4
print('en dias tienes' ,resultado,'segundos')
print('en horas tienes' ,resultado2, 'segundos')
print('en minutos tienes' ,resultado3,'segundos')
print('en segundos tienes' ,resultado4,'segundos')
print('tienes un total de' ,resultado5,'segundos')



C�digo 14: # edad humano a edad perro
En este c�digo el equipo va desplegar un mensaje donde te va pedir que insertes la edad que quisieras averiguar c�mo edad perro y el equipo va desplegar en mensaje donde va decirte cuantos a�os tienes de perro y va desplegar otro mensaje donde va decir que no se aceptan n�meros negativos.

edad=float(input('introduce el numero de edad que quieres conocer en edad perro: '))
e1= 2
e2= 1
e3= edad *4-10.5
if edad==e1:
    print('la conversion en edad perro es: 10.5 en anios humanos:')
elif edad == e2:
    print('la conversion en edad perro es: 5.25 en anios humanos:')
elif edad > e1:
    print('la conversion en edad perro es: ',e3)
elif edad < e2:
    print('lo siento no se permiten negativos , ingresalo de nuevo')
 

C�digo 15: # n�mero par e impar 
En este en equipo le va a preguntar al usuario que inserte un n�mero y el equipole va decir que el n�mero es par e impar.


 n = int(input('Inserta cualquier numero: '))
if n%2 == 0:
   print('El nuero es par')
elif n%2 != 0:
    print('El numero es inpar')





C�digo 16: #  import time 
En este c�digo cuando el usuario lo ingrese en el lenguaje de programaci�n python el equipo va a desplegar una impresi�n  la fecha y ha hora del equipo.


 import time
print('la hora actual es ',time.strftime("%I:%M:%S"))
print('la fecha actual es ',time.strftime("%d/%m/%y"))



# import math 

# �Qu� es?
Import math es una librer�a de python la cual es para realizar multiplicaciones, rango, o un resultado que el usuario quiere realizar esta librer�a facilita a un programador a realizar c�lculos matem�ticos en el lenguaje python.



C�digo 17: # latitud de la tierra en kil�metros
En este c�digo el equipo va desplegar un mensaje diciendo que inserte la latitud y va desplegar varios mensajes donde deber�s de insertar diferentes latitudes de la tierra y el equipo va realizar el conteo de cuanta latitud de la tierra en kil�metros.
 

from math import degrees,sin,cos,acos
latitud=(float(input('ingresa latitud:')))
longitud=(float(input('ingresa longitud:')))
latitud2=(float(input('ingresa latitud:')))
longitud2=(float(input('ingresa longitud:')))
distancia= 6371.01*acos(sin(latitud)*sin(latitud2)+cos(latitud)*cos(latitud2)*cos(longitud-longitud2))
distancia2=degrees(distancia)
print('la distancia es',distancia2,'km')


C�digo 18: # radio de la esfera.
En este c�digo en equipo va a desplegar un mensaje donde te pregunte que insertes el radio  de la esfera y el equipo va realizar el c�lculo y va a imprimir el volumen de la esfera en cent�metros cuadrados.

import math
radio=float(input('ingresa el radio;'))
area= math.pi*(radio**2)
volumen= 4/3*3.1416*(radio**3)

print('el area del circulo es:',area,'cm cuadrados')
print('el volumen del circulo es:' ,volumen,'cm cubicos')

 



C�digo 19: # posici�n de cuadro de ajedrez 
En este c�digo el equipo va desplegar un mensaje que el usuario inserte una coordenada y que el equipo despliegue el color del cuadro de la posici�n que el usuario inserto.

x=input('ingresa la corderdenada en letra')
y=int(input('ingresa la corderdenada 2 en numero'))
a=y%2
if x == a :
     print('es blanco')
elif:
    print('es negro')
 


C�digo 20: # estatura 
En este c�digo el usuario va a insertar su estatura y el equipo va a imprimir la estatura en cent�metros cuadrados.

 pies = 2.54 centimetros
Pulgadas = 12 pulgadas
metros = 100 cm
estatura de Gabby = 150 centimetros
print('Cual es la estatura de Gabby en pies')
print('Cual es la estatura de Gabby en pulgas')
print('150 centimetros * 12 pulgadas')
print('150 centimetros * 2.54 centimetros')



C�digo 21: # metros equivalentes 
En este c�digo el equipo va desplegar dos mensajes uno diciendo que inserte un numero de milla y el otro que inserte un numero de pulgadas y el equipo va imprimir un equivalente de metros obtenidos.

 print('obten elequivalente en metros de los siguientes datos')
pies= float(input("inserta elnumero de millas: "))
pulgadas= float(input("inserta el numero de pulgadas: "))
metros= 0.3048 * pies + 0.0254 * pulgadas
print('tienes un equivalente de' ,metros, 'metros')


C�digo 22: # �rea del triangulo 
En c�digo el equipo va desplegar un mensaje diciendo que inserte el valor de b y otro mensaje dici�ndole que inserte el valor de h y ya que el usuario inserte los valores el equipo va realizar un c�lculo donde va realizar la suma para realizar el �rea del tri�ngulo.

 print('calcular el area de un triangulo usando b y h')
longitud=float(input('inserta cuando medira b: '))
b=longitud
altura=float(input('inserta cuanto medira h: '))
h=altura
area= b * h / 2
print('el area del triangulo es' ,area, 'centimetros cuadrados')



C�digo 22: # distancia recorrida 
En este c�digo el equipo va desplegar un mensaje diciendo que inserte la distancia recorrida en kil�metros de un taxi y el equipo  va realizar un c�lculo donde de dir� al usuario cuanto es lo que debe por los kil�metros recorridos.

 ilo=input('ingrese la distancia recorrida en kilometros:')
def tarifa(ilos):
    return (40+7*ilo)
    resultado=tarifa(ilos)
print(resultado)


C�digo 23: # descuento
En este c�digo el equipo va desplegar un descuento ingresado en el codigo y va a imprimir cuanto fue el descuento.

for precio in range (4,5,199):
    descuento= precio * 60 /100 + 0.95
    print(precio,'|',descuento)
    

 
C�digo 24: # suma 
En este c�digo el equipo va realizar un mensaje dici�ndole al usuario que inserte una suma que quiera realizar y equipo le va decir cu�nto es el resultado de su suma.

 numero=int(input('ingresa un numero:'))
suma=(numero*(numero+1))/2
print(suma)


C�digo 25: #  grafica 
En este c�digo el equipo y va mostrar al usuario un mensaje dici�ndole que seleccione una opci�n de una gr�fica seleccionada y el equipo va desplegar una gr�fica requerida.
 
import numpy as np
import matplotlib.pyplot as plt
print('Que quieres graficar: 1.seno 2.coseno 3.tangente , elige una opcion')
op=int(input('escribe tu opcion:'))
x=np.arange(100)
if op == 1:
    y=np.sin(x) 
elif op== 2:
    y=np.cos(x) 
elif op==3:
    y=np.tan(x)     

plt.plot(x,y) 
plt.show()



C�digo 26: # password 
En este c�digo el equipo va desplegar un mensaje dici�ndole al usuario que inserte un nuevo password y despu�s llenara de nuevo su nuevo password y el equipo va enviar un mensaje al usuario de que su password ha sido establecido o si se equivoca de contrase�a le saldr� un mensaje diciendo que es incorrecto y por ultimo gracias.  
 
password_user1 =  input('Inserte un  nuevo password: ')
password_user2 =  input('Confirme su password: ')
 
if password_user1 == password_user2:
    print('Su password ha sido establecido')
else:
    print('Lo sienti, ha introducido mal los datos')
print('Gracias!')

C�digo 27:# C�lculo del �ndice de masa corporal
En este c�digo el equipo va desplegar un mensaje dici�ndole al usuario que inserte  su peso en kilogramos y su altura y el equipo le va decir al usuario si est� muy bien de salud o tiene obesidad nivel alto o esta desnutrido.

 # Calculo del indice de masa corporal

masa = float(input('Introduce tu peso en kg: '))
altura = float(input('Introduce tu altura en metros: '))
imc = masa/altura**2
if imc < 16:
    print('Tienes delgadez severa')
elif imc >= 16 and imc < 17 :
   print('Tienes delgadez moderada')
elif imc >= 17 and imc < 18.5 :
   print('Tienes delgadez leve')
elif imc >= 18.5 and imc < 25 :
   print('Tienes el IMC correcto')
elif imc >= 25 and imc < 30 :
   print('Tienes obecidad')
elif imc >= 30 and imc < 35 :
   print('Tienes obecidad leve')
elif imc >= 35 and imc < 40 :
   print('Tienes obecidad morbida')
else:
   print('Favor de introducir datos correctos')
print('Gracias!')





C�digo 28: # signo zodiacal 
En este c�digo el equipo va desplegar un mensaje que ingrese el d�a y el mes de cuando naci� y el equipo va a desplegarte que signo zodiacal eres por tu mes de nacimiento.

dia = int (input ('Ingresa el dia en que naciste: '))
mes = int (input ('Ingresa el mes en que naciste: '))

if (dia>=21 and mes==3) or (dia<=20 and mes==4):
    print ('Aries')
if (dia>=24 and mes==9) or (dia<=23 and mes==10):
    print ('Libra')
if (dia>=21 and mes==4) or (dia<=21 and mes==5):
    print ('Tauro')
if (dia>=24 and mes==10) or (dia<=22 and mes==11):
    print ('Escorpio')
if (dia>=22 and mes==5) or (dia<=21 and mes==6):
    print ('geminis')
if (dia>=23 and mes==11) or (dia<=21 and mes==12):
    print ('Sagitario')
if (dia>=21 and mes==6) or (dia<=23 and mes==7):
    print ('canncer')
if (dia>=22 and mes==12) or (dia<=20 and mes==1):
    print ('Capricornio')
if (dia>=24 and mes==7) or (dia<=23 and mes==8):
    print ('Leo')
if (dia>=21 and mes==1) or (dia<=19 and mes==2):
    print ('Acuario')
if (dia>=24 and mes==8) or (dia<=23 and mes==9):
    print ('Virgo')
if (dia>=20 and mes==2) or (dia<=20 and mes==3):
    print ('Piscis')
print ()


 
C�digo 30: # grados 
En este c�digo el equipo va desplegar un mensaje dici�ndole al usuario que ingrese la temperatura en grados Celsius y el equipo los va a convertir a grados farenheit.

 

 # Ejercicios librer�a class
Class es una librer�a donde puedes crear una clase con un def la cual se puede ocupar para conversi�n o para realizar canciones que el equipo se la escriba al usuario.


C�digo 31: # ma�anitas 
En este c�digo el equipo va desplegar las ma�anitas cuando se ejecute el c�digo en el lenguaje python 

 class cancion(object):
    def _init_(self,letra):
        self.letra=letra

    def feliz_cumple(self):
        if self.letra:
            print('estas son lasma�anitas que cantaba el rey david, hoy por ser dia de tu santo de las cantamos a aqui')
        


C�digo 32: #  gasolina 
En este c�digo el equipo va realizar el llenado de las bombas de gasolina en usuario inserta el monto que desea llenar asu carro y el equipo va ir contando cuantos litros se le deben de dar al usuario.

class Coche(object):
   def __init__(self,gasolina):
       self.gasolina = gasolina
   def arrancar(self):
       if self.gasolina>0:
           print('arrancar')
       else:
           print('no arranca pendejo')
   def conducir(self):
       if self.gasolina>0:
          self.gasolina = self.gasolina - 1
          print('quedan',self.gasolina,'litro')
       else:
           print('no se mueve')

vocho = vocho(5)
tsuru = coche(3)
vocho.arrancar()
vocho.conducir()
vocho.conducir()
vocho.conducir()
vocho.conducir()
vocho.conducir()
vocho.conducir()
 


C�digo 33: # �ngulos
En este c�digo en equipo va mostrar opciones de los �ngulos y el usuario va seleccionar uno y el equipo ya a imprimir si es verdadero o falso. 

 class triangulo:
    def __init__(self,triangulo1,triangulo2,triangulo3):
        self.angulo1=angulo1
        self.angulo2=angulo2
        self.angulo3=angulo3
    def checar_angulos(self):
        if self.angulo1 + self.angulo2 + self.angulo3== 180:
           print('es verdadero')
        else:
           print('es falso')

mitriangulo = triangulo(90,30,60)
mitriangulo.checar_angulos()


# Gr�ficos 
Import turtle 
Import turtle es una librer�a de python que se pueden realizar diferentes graficos como onda con im�genes, etc.estos programas van a desplegar una imagen en movimiento, Unos de los motivos que inspiraron el desarrollo de Python fue contar con una herramienta que uniera la posibilidad de realizar c�lculos avanzados con la obtenci�n de representaciones gr�ficas de los propios datos que facilitaran su an�lisis con la librer�a turtle.

 
# Import turtle 

C�digo 34:# pol�gono 
Con este c�digo el usuario va a ejecutar el c�digo y el equipo va realizar un pol�gono 

import turtle

def dibujar_poligono(tur , d):
    for i in range(8):
        tur.forward(d)
        tur.left(45)

ventana = turtle.Screen()
ventana.bgcolor('white')
ventana.title('funciones')

hush = turtle.Turtle()
hush.speed(1)
dibujar_poligono(hush, 50)
ventana.mainloop 
 

 
C�digo 35 # gato
En este c�digo la imagen pasara el posici�n x hasta la posici�n deseada.
 
import turtle

window= turtle.Screen()
window.addshape('nicolas.gif')
border= turtle.Turtle()
border.speed(0)
border.up()
border.hideturtle()
border.pensize(5)
border.color('white')
border.goto(300,300)
border.down()
border.goto(300,-300)
border.goto(-300,-300)
border.goto(-300,300)
border.goto(300,300)


gato=turtle.Turtle()
gato.speed(1)
gato.shape('nicolas.gif')

gato.up()
dx=1

while True:
    x,y= gato.position()
    if x+dx>=300 or x+dx<=-300:
        dx=-dx
   
    gato.goto(x+dx,y)

window.mainloop()
 




C�digo 36: # gatos
En este grafico la imagen avanzara y cuando llegue a la posici�n indicada de va a regresar y as� secativamente hasta que el usuario guste.
 
import turtle

window= turtle.Screen()
window.addshape('nicolas.gif')
border= turtle.Turtle()
border.speed(0)
border.up()
border.hideturtle()
border.pensize(5)
border.color('white')
border.goto(300,300)
border.down()
border.goto(300,-300)
border.goto(-300,-300)
border.goto(-300,300)
border.goto(300,300)


gato=turtle.Turtle()
gato.speed(1)
gato.shape('nicolas.gif')

gato.up()
dx=1

while True:
    x,y= gato.position()
    if x+dx>=300 or x+dx<=-300:
        dx=-dx
   
    gato.goto(x+dx,y)

window.mainloop()
 



C�digo 37: # espiral 
En este c�digo en equipo va realizar un espiral en forma de cuadro en cual se muestra continuaci�n
 
 
import turtle
def spiral(t,side):
  for i in range(2):
    #t.speed(0)
    t.forward(side)
    t.left(89)
    spiral(t,side+10)
t=turtle.Turtle()



C�digo 38: # tortugas en x
En este grafico las tortugas se va a mover en forma de un asterisco como se ve a continuaci�n 
 
 mport turtle
import time
from math import sin, pi
from random import random


def circle_dance(population=11, resolution=480, loops=49, flip=0, lines=0):
    population = int(population)
    resolution = int(resolution)
    radius = 250
    screen = turtle.Screen()
    screen.tracer(0)
    if lines:
        arrange_lines(population, radius)
    turtles = [turtle.Turtle() for i in range(population)]
    for i in range(population):
        dancer = turtles[i]
        make_dancer(dancer, i, population)
    animate(turtles, resolution, screen, loops, flip, radius)


def arrange_lines(population, radius):
    artist = turtle.Turtle()
    for n in range(population):
        artist.penup()
        artist.setposition(0, 0)
        artist.setheading(n / population * 180)
        artist.forward(-radius)
        artist.pendown()
        artist.forward(radius * 2)
    artist.hideturtle()


def make_dancer(dancer, i, population):
    dancer.setheading(i / population * 180)
    dancer.color(random_turtle_colour())
    dancer.penup()
    dancer.shape('turtle')
    dancer.turtlesize(2)


def random_turtle_colour():
    return random() * 0.9, 0.5 + random() * 0.5, random() * 0.7


def animate(turtles, resolution, screen, loops, flip, radius):
    delay = 4 / resolution      # 4 seconds per repetition
    while True:
        for step in range(resolution):
            timer = time.perf_counter()
            phase = step / resolution * 2 * pi
            draw_dancers(turtles, phase, screen, loops, flip, radius)
            elapsed = time.perf_counter() - timer
            adjusted_delay = max(0, delay - elapsed)
            time.sleep(adjusted_delay)


def draw_dancers(turtles, phase, screen, loops, flip, radius):
    population = len(turtles)
    for i in range(population):
        individual_phase = (phase + i / population * loops * pi) % (2*pi)
        dancer = turtles[i]



C�digo 39: # c�rculos 
En este grafico dos tortugas realizaran dos c�rculos uno de 50 y el otro de 100 como se muestra.
 

 print('Escribe uno de los siguiente colores:blue,lightgreen,azure1,azure2,bisque3,brown,aquamarine1,aliceblue,white')

import turtle
m=input("ingresa el color de tu ventana:")
c=int(input('ingresa el numero de vueltas:'))
k=int(input('ingresa la velocidad:'))
ventana=turtle.Screen()
ventana.bgcolor(m)
ventana.title("Hola, edwin")


jessie=turtle.Turtle()
for i in range(c):

     jessie.shape("turtle")
     jessie.color("black")
     jessie.pensize(4)
     jessie.speed(k)
     jessie.penup()
     jessie.setpos(0,-10*i)
     jessie.pendown()
     jessie.circle(10*i)
ventana.mainloop()

     
    
C�digo 40: # cuadros 
En esto c�digo se realizaran cuadros hacia la posici�n x dependiendo del los cuadros que el usuario guste.
 

 import turtle

def dibujar_cuadros_multiples(tur, d):
    for i in range(4):
       
        tur.forward(d)
        tur.left(90)



ventana= turtle.Screen()
ventana.bgcolor('lightgreen')
ventana.title('Funciones')
hush=turtle.Turtle()
hush.pensize(4)
dibujar_cuadros_multiples(hush,20)
d = 20

for i in range(17):
    dibujar_cuadros_multiples(hush, d)

    hush.penup()
    hush.forward(50)
    hush.pendown()


ventana.mainloop()




C�digo 41: # senoidal
En este grafico el equipo mover� la imagen en forma de onda de arriba para abjao
 
 p1, = plot(sin(x))       

figure(2)                
      
title('Funcion coseno')  
figure(1)                
title('Funcion seno')  
subplot(131)
p1, = plot(x,f1(x),'r-')

ylabel('Amplitud / cm')
title('Funcion 1')



C�digo 42 #  circulo con cuadros.
En este grafico el equipo va ir realizando cuadros y formando un circulo de 90 grados
 

import turtle
wn = turtle.Screen()
wn.bgcolor('lightgreen')
hush = turtle.Turtle()
hush.pensize(2)
hush.color('blue')

def first_two_line(size):
    hush.right(180)
    hush.forward(size)
    hush.right(90)
    hush.forward(size)

def draw():
    size = 10
    first_two_line(size)
    for i in range(40):
        size += 5
        hush.right(90)
        hush.forward(size)
        hush.right(90)
        hush.forward(size)
draw()
wn.mainloop()
 





C�digo 43 # cuadros
en este grafico una tortuga va ir realizando cuadros tras cuadros y se va parar cuando termine de contar los cuadros que el usuario inserto.
 
import turtle

def draw_square(some_turtle):
    for i in range(0,4):
        some_turtle.forward(100)        
        some_turtle.right(90)          

def draw_art():        
    
    ventana = turtle.Screen()
    ventana.bgcolor("red")     

    
    hush = turtle.Turtle()
    hush.shape("turtle")      
    hush.color("yellow")      
    hush.speed(6)             

    
    for i in range (0, 36):
        draw_square(hush)
        hush.right(10)

  
draw_art()
 




C�digo 44  # arco
En este grafico se va realizar un arco formado por cuadros como se muestra a continuaci�n

import turtle
import math

window= turtle.Screen()
window.addshape('nicolas.gif')
window.setworldcoordinates(0,-1,1000,1)
border= turtle.Turtle()
border.speed(0)
border.up()
border.hideturtle()
border.pensize(5)
border.color('white')
border.goto(300,300)
border.down()
border.goto(300,-300)
border.goto(-300,-300)
border.goto(-300,300)
border.goto(300,300)


gato=turtle.Turtle()
gato.speed(1)
gato.shape('nicolas.gif')

gato.up()
dx=1

while True:
    x,y= gato.position()
    y=math.sin(math.radians(x))
    if x+dx>=300 or x+dx<=-300:
        dx=-dx
   
    gato.goto(x+dx,y)

window.mainloop()
 
