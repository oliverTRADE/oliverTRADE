import random

def jugar():
    print("¡Bienvenido al juego de ganar megas!")
    print("Haz clic en el enlace para ganar 1000 megas.")

    # Simular la elección del usuario de hacer clic o no en el enlace
    eleccion = input("¿Quieres hacer clic en el enlace? (s/n): ").lower()

    if eleccion == 's':
        print("¡Felicidades! Has ganado 1000 megas.")
    else:
        print("Oh no, has recibido una carta en lugar de megas.")
        mostrar_carta()

def mostrar_carta():
    print("Esta carta va dedicada con mucho cariño para ti:")
    print("Querida Yaneth,")
    print("Eres una niña muy linda y solo quisiera decirte que me haces mucha falta.")
    print("Te amo mucho.")
    
if __name__ == "__main__":
    jugar()

