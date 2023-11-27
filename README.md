# 4100901-final-exam
This repo shall be used by the students to implement the requirements specified for the final exam.

## Requirements

0. El dispositivo se debe basar en la NUCLEO-L476RG y la pantalla OLED SSD1306.
1. El dispositivo debe mostrar el mensaje *"Waiting"* en modo normal.
2. El dispositivo debe poder recibir comandos desde un computador.
3. El dispositivo debe procesar los comandos recibidos del PC de la siguiente forma:
  * Si el commando corresponde a su código de estudiante debe mostrarse un mensaje de *"Success"* en la pantalla OLED durante 10 segundos.
  * Si el comando es erróneo debe mostrarse un mensaje de *"Failed"* en la pantalla OLED durante 10 segundos.
4. Si se fallan 3 intentos seguidos, el dispositivo debe mostrar *"Blocked"* en la pantalla OLED y esperar 30 segundos hasta volver a su estado normal.
