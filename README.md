# webusb serial terminal
https://selevo.github.io/WebUsbSerialTerminal/

webusb ch340 ft232and etc. terminal  work on android browser.
default 57600
_____________
webapi WEBusb serial - will work in android.

webapi WebSerial - will not work on android

this is a very important difference between these two webapi
_____________
репозиторий состоит из двух файлов которые были скопированы со страницы по этой ссылке:
https://stackoverflow.com/questions/64929987/webusb-api-working-but-the-data-received-arent-decoded-properly
и оформленные в виде одной веб-страницы для примера.

Спасибо автору, он проделал большую работу терминал работает на смартфоне на базе Android. 
у меня возникли некоторые проблемы с отключением устройства поэтому новый экземпляр страницы может не запуститься без переподключения usb-com свистульки.
то есть браузер автоматически не отключает устройство если страница была закрыта 
также не работает кнопка disconnect.

если кто-то доработает то я буду рад, и все остальные тоже.
А вот более законченный проект того же автора: 
https://grovkillen.com/webusb/
Он имеет также некоторые проблемы если использовать смартфон, происходит перезагрузка смартфона иногда в тот момент когда вытаскиваешь устройство из смартфона. автор сообщил что это глюк хром браузера.

2025-12-12~14_38_09

На текущий момент,  код  работает не везде из-за изменившихся методов рабты   браузера с  USB  устройствами.
Возможно потребуется  подмена имени устройств с помощью https://zadig.akeo.ie/
Так же  смотрите развитие проекта  автора (grovkillen) https://github.com/letscontrolit/ESPEasy?tab=readme-ov-file
Там  были  исключены   все  WEB USB API и  теперь используются WEBserial API ( поэтому будет работать только на компьютере и не  будет работать  в браузере на android)


English ^^
The repository consists of two files that were copied from the page at this link: https://stackoverflow.com/questions/64929987/webusb-api-working-but-the-data-received-arent-decoded-properly and formatted as a single web page for example.

Thanks to the author, he did a great job. The terminal works on an Android smartphone. I had some issues disconnecting the device, so a new page might not launch without reconnecting the USB-COM device. That is, the browser doesn't automatically disconnect the device if the page is closed, and the disconnect button doesn't work.

If someone improves it, I'll be happy, and so will everyone else. Here's a more complete project by the same author: ~~https://grovkillen.com/webusb/~~ It also has some issues when using a smartphone; the smartphone sometimes reboots when you remove the device from the smartphone. The author reported that this is a Chrome browser glitch. 
![Screenshot_20230913_040225_com android chrome](https://github.com/selevo/WebUsbSerialTerminal/assets/13694921/1d808fe0-d964-4601-b5a4-04428f0c6b25)

(2025-12-12~14_38_09

Currently, the code doesn't work everywhere due to changes in the browser's handling of USB devices.
You may need to change the name using https://zadig.akeo.ie/
Also see the author's (grovkillen) project development: https://github.com/letscontrolit/ESPEasy?tab=readme-ov-file
All WEB USB APIs have been removed and the WEBserial API is now used (so it will only work on a computer and will not work in an Android browser).)
about://usb-internals
![Screenshot_20230913_071718](https://github.com/selevo/WebUsbSerialTerminal/assets/13694921/da16214d-5a48-4a8d-9ece-db436bd7a682)

