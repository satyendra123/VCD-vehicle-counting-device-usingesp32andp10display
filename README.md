# VCD-vehicle-counting-device-usingesp32andp10display
i have used the two loop detector which detects the car metal. 

connection is something like this. there are two signals comes out from each loop com and No. so what have i done is i have made both the com wire common and connected with esp32 gnd pin. and i have taken the NO wire and connected with the esp32 pin p4 and p5. the entry loop NO pin is connected with the p4 of esp32 and the exit loop NO pin is connected with the p5 of esp32. i have used the single channel loops. the connection of the loop is very simple. we are connecting the wire to the pin 1,2 and making a wire loop and also making the both the loops power to common. and taking the out signal NO and com out from the loop detector.
