Supongamos un disco con un tamaño de sector de 512 bytes y que las direcciones que apuntan a
esos sectores son de 32 bytes. ¿Cual es el máximo tamaño que puede tener el disco?

Con 32 bytes podemos formar 2**32 direcciones. Si cada dirección apunta a un sector, entonces 
el número total de bytes accesibles es 512 * 2**32 que son aprox. 2TiB.

Si el disco es mayor tendrá sectores sin usar porqué no hay bastantes direcciones para apuntar
a todos los sectores disponibles.