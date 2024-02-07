# longitud_de_una_frase.py
#Solicitar al usuario que ingrese una palabra
palabra = input("Ingrese una palabra: ")

#Obtener la longitud de la palabra ingresada
longitud = len(palabra)

#Comprobar las condiciones y mostrar mensajes correspondientes
if 4 <= longitud <= 8:
    print("La palabra es correcta. ")
elif longitud < 4:
    print(f"Hcaen falta letras. Solo tiene {longitud} letras. ")
else:
    print(f"Sobran letras. La palabra tiene {longitud} letras. ")
     
