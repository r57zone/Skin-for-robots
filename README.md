<h2>RU: Датчик чувствительности для роботов</h2>

![](https://github.com/r57zone/Skin-for-robots/blob/master/skin.png)<br>
Простой датчик чувствительности для роботов. При нажатии графитовая кнопка замыкает контакты. Имеет 3 позиции: 25% - легкое нажатие, 50% среднее и 75% сильное. 
<br><br>
Сначала замыкается первая позиция, из-за маленькой толщины стенок, она легче нажимается и за счет этого контакты замыкаются раньше чем у других позиций. Остальные замыкаются аналогично, поочередно.
<br><br>
Чтобы датчик имел всего 1 пин, нужно замыкать резисторы в цепь, а получать значения путем измерения напряжения, например, на Arduino через аналоговый пин и функцию analogRead().
<br><br>
<h2>EN: Sensitivity sensor for robots</h2>
Simple sensor sensitivity for robots. Pressing the button closes the graphite contacts. It has 3 positions: 25% - a slight depression, 50% average and 75% stronger.
<br><br>
First closes the first position, due to the small wall thickness, it is easily pressed and thereby contacts close earlier than at other positions. The rest is similar to closed alternately.
<br><br>
To sensor had just one pin, you need to add the resistors in the circuit, and get values by measuring the voltage, for example, on the Arduino via analog pin and function analogRead().
