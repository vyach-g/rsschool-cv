# Vyacheslav Grabovskiy
### Trainee Frontend-Developer
===
## Contacts
+ **E-mail:** vyacheslav.grabovskiy@gmail.com
+ **Phone:** 8 800 555 35 35
+ **Telegram:** strad1e
===
## About myself

The computer appeared early, so the future was predetermined. Graduated from the university with a degree in telecommunications, now I work as a network engineer. In my free time I do web development and design. I started learning programming with python, but I realized that the frontend is closer to me, that's why I'm here. 
===
## My Skills
+ **Development:** HTML/CSS, JavaScript, Python, Git
+ **Adminstration:** CCNA, Windows, Linux
+ **Design:** Figma, Photoshop, Illustrator, AfterEffects, Blender
===
## Code sample
### guessNumber game script
```
var randomNumber
var guessNumber
var value

newRandom = function() {
    randomNumber = Math.floor(Math.random()*100)
    console.log(randomNumber)
}

document.querySelector("#inp").addEventListener("keyup", event => {
    if(event.key !== "Enter") return;
    document.querySelector("#butt").click();
    event.preventDefault();
});

attempt = function() {
    value = document.getElementById('inp').value;
    if (value==randomNumber) {
        document.getElementById('res').innerHTML="<b>Вы угадали!</b><br>Загадано новое число";
        newRandom();
    } 
    else if (value<0) document.getElementById('res').innerHTML="Только положительные <br> числа";
    else if (value-randomNumber>0 && value-randomNumber<10) document.getElementById('res').innerHTML="Загаданное число <br> немного меньше";
    else if (value-randomNumber>=10 && value-randomNumber<100) document.getElementById('res').innerHTML="Загаданное число <br> много меньше";
    else if (randomNumber-value>0 && randomNumber-value<10) document.getElementById('res').innerHTML="Загаданное число <br> немного больше";
    else if (randomNumber-value>=10 && randomNumber-value<100) document.getElementById('res').innerHTML="Загаданное число <br> много больше";
    else document.getElementById('res').innerHTML="Вводите числа";
};

newRandom()
```
## Experience
Date | Place of Work | Position | Duties
-|-|-|-
04.2020-now| JSC KT | **Network Engineer**|*Network administration, server and network equipment configuration and maintaince*
02.2019-now| WIZOUD Digital-Studio | **Project manager** | *Project management, design, team collaboration*
## Study
Date | Place of Study | Speciality
-|-|-
09.2016-06.2020 | NKZU | **Radio Engineering, Electronics and Telecommunications**
10.2020-12.2021 | Stepik | **Python Development Online-Courses**
06.2021-08.2021 | Coursera| **HTML/CSS/JS Basics Online-Courses**
## Languages
+ **Russian:** Native
+ **English:** B1
+ **Kazakh:** A2
+ **German:** A2