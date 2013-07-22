task-force-arma-3-radio
=======================

Arma 3 Team Speak Radio Plugin

Инструкция по установке:

* Скачайте архив https://github.com/michail-nikolaev/task-force-arma-3-radio/raw/master/releases/0.2%20pre%20alpha.zip
* Убедитесь, что в Team Speak клавиша Caps Lock не используется для разговора
* Отключите в ARMA 3 разговор по внутренней рации по нажатию Caps Lock (чтобы не двоиться)
* Скопируйте содержимое папки Arma 3 в `....\SteamApps\common\Arma 3` (папку с игрой)
* Скопируйте содержимое `TeamSpeak 3 Client\x32` в папку с TeamSpeak если он 32-ух битный, или `TeamSpeak 3 Client\x64`, если 64-ёх
* Чтобы узнать, какой у вас TeamSpeak поищите файл `ts3client_win64.exe` или `ts3client_win32.exe` в папке с Team Speak
* Запустите Team Speak, зайдите на любой сервер, кликните правой кнопкой на вашем канале и выберите `Setup 3D Sound`, установите галочку `Enable 3D Sound` справа снизу
* Откройте список плагинов в Team Speak, включите `Task Force Arma 3 Radio`, отключите `ACRE` и `radio ts ARMA3.ru version`, чтобы избежать конфликтов
* Можно на всякий случай перезапустить Team Speak :)
* Запустите игру с аддонами `CBA_A3` и `@task_force_radio` (Community Base Addons: A3 Beta и Task Force 141 Radio), это можно сделать командой `arma3.exe -mod:@CBA_A3;@task_force_radio`
* Убедитесь, что ник в игре и Team Speak совпадает (если вы используете squal url, то добавляемый им в конец ника тэг не стоит ичитывать)
* Убедитесь, что громкость звуков в Team Speak не отключена (Options -> Payback -> Sound Pack Volume установите на максимум +0db)
* Рекомендуется отключить звуки-оповещения TeamSpeak: Options -> Notifications -> Sound Pack: "Sounds Deactivated" (применится только после перезапуска Team Speak)
* Зайдите в тот же канал, где и другие игроки с данной рацией

Управление:
* Используйте кнопку голоса в Team Speak, чтобы говорить прямой речью
* Используйте Caps Lock, чтобы говорить по рации


На всякий случай:
* Если из-за падения или еще чего-то вы перестали слышать других игроков даже вне игры, откройте `Setup 3D Sound` и скликните `Center All`

Администраторам TeamSpeak серверов:
* Уменьшите уровень защиты от флуда - правый клик по серверу -> Edit Virtual Server -> More -> Anti Flood, поставьте значения 30, 300, 3000 (сверху вниз)