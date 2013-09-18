motor_characterization
======================

motor_characterization script for josé Ávila: encoder position in function of the indexer position.

/mrosanes/scripts/

How to use description:
python motor_characterization   icepap_host   axis   lower_pos   higher_pos   steps_interval

donde:
nombre del script: motor_characterization
icepap host: icesat01
axis: 16 (el eje del motor que tiene que hacer el movimiento que quieres caracterizar)
lower_pos: Indexer intital value (aquí puedes poner lo que quieras, siempre que sea inferior al valor final)
higher_pos: Indexer final value (aquí pueses poner lo que quieras, siempre que sea superior al valor inicial)
steps_interval: Intervalo que deseas para la toma de valores en cuentas de indexer. En el ejemplo he puesto 2000, eso quiere decir que cada 2000 cuentas de indexer se tomaran los valores de indexer/encoder.


Para lanzarlo, tienes que ir a la carpeta donde está el script: operator@ictblsat01:~/mrosanes/scripts/
y hacer:

python motor_characterization icesat01 16 1330000 1340000 2000

En donde el 1330000, el 1340000 y el 2000 pueden ser los que tu desees.

