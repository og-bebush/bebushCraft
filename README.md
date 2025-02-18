# bebxsh_craft
## Общая информация

> _IP: mc.bebxsh.org_
> 
> _Version: 1.21.4_
> 
> _API: Fabric_

<hr>

<a name="contents">
 
## **Содержание**

> 1. [Планировка](#planv2)
> 2. [Гайд по сборке/подключению](#guide)
> 3. [Модлист](#modlist)
> 4. [Референсы построек](https://discord.com/channels/1175777541278154823/1336775889039392788)

<hr>
<br>

<a name="planv2">
 
## **PLAN V2**

**Общая задумка -  разбить город на районы.**
Районы должны быть с разными культурами (китай + япония, франция + англия, римская/египет) и иметь свою "задачу".
Пример районов:
> 1. Cкандинавы (порт)
> 2. Aзиаты (продавцы)
> 3. Eвропа (индустриальный)

<hr>

Обязательные районы:
> 1. Порт
> 2. Магический
> 3. Индустриальный

<hr>

Зона игроков (вне зоны проекта):
> фермы, фишки, постройки - в общем и целом, зона чисто под нас

<hr>

### **Разметка**

Город разбит на несколько районов, имеет несколько "слоев" (каждый слой выше предыдущего), слои отделены стенами.
На вершине должен стоять замок или какая-то гигантская постройка, которая считается главным зданием.
*есть идея сделать супер большую постройку, внутри которой можно разместить нашу базу со всеми авто-фермами, складом и т.д.*

С одной боковой стороны должен быть выход к морю, где будет порт
Должен быть обрыв, как смотровая площадка на весь город.

<hr>
<br>

<a name="guide">
 
## **ГАЙД ПО УСТАНОВКЕ И ПОДКЛЮЧЕНИЮ**
*Полноценный гайд в стадии разработки, пока довольствуйтесь этой хуйней*

<hr>

**Подготовка к установке**

1. _**SKLauncher**_ *(наша тема)*
Нужны: [лаунчер](https://skmedix.pl/downloads), мозг *(опционально)*
>
> 1.1 Открываем сайт с лаунчером по ссылке выше **(суки не дадут скачать с адблоком)**
> 
> 1.2 Скачиваем по **второй кнопке** - "Download x64 .exe"
> 
> 1.3 Запускаем лаунчер
>  *Если выдает ошибку про Java/JDK/JRE - скачайте джаву с [оффсайта](https://www.oracle.com/java/technologies/downloads/#jdk23-windows)*
> 
> 1.4 Снизу есть серая кнопка "Войти в оффлайн режиме"
> 
> 1.5. Вводим ник и нажимаем на "Войти"
> 
> 1.6 Слева сверху есть "Менеджер сборок", нажимаем на "+" рядом с ним
> 
> 1.7 Нажав на блок можете выбрать икноку, дальше дайте название вашей сборки (че угодно, но на англ языке)
> 
> 1.8 Под текстом "Версия" выбираете "Fabric"
> 
> 1.9 Слева должна быть версия "1.21.4", справа "0.16.10"
>
> 1.10 Жмем "Сохранить"
> 
> 1.11 В левом меню выбираем вашу сборку и нажимаем на "Играть"
> 
> 1.12 Закрываем майнкрафт

<hr>
<br>

 ***Дальше листайте до "[установка-сборки](#guide2)"***

 <br>

> Нужны: лаунчер, [fabric](https://fabricmc.net/use/installer/), мозг
> ***TLauncher - блядское говно, качайте что-то другое***
>
> 1. Убедитесь, что папка с майном чистая (нет других фабриков/модов)
> 2. Скачиваем **Fabric 0.16.10** по ссылке выше
> 3. Открываем файл, оставляем все как есть, нажимаем на "Готово"
> 4. В блядском лаунчере, в верху списка, должна появится версия *"fabric-loader-0.15.10-1.20.5"*
> 5. Все готово
> **Дальше листайте до "установка сборки"**

<hr>

<a name="guide2">
 
**Установка сборки и коннект**

> 1. Скачиваем зип со сборкой выше **client-pack.zip**
> 2. Скидываем  **все папки/файлы внутри архива** в **корневую** папку **(.minecraft)**
> 3. Заходим в майнкрафт -> мультиплеер -> добавить сервер -> в поле с айпи пишем: **13.60.49.100**


<hr>
<br>

<a name="modlist">
 
## **МОДЛИСТ**
_Пока сборка только решается, если есть предложения ВАНИЛЬНЫХ модов для серва/локалки - питшите_
:exclamation:Сборка на Fabric:exclamation:

> **серверные**
> 1. [CoordFinder](https://modrinth.com/mod/coord-finder) - команды на корды
> 2. [Armor Poser](https://modrinth.com/mod/armor-poser) - разные позы для стенда брони
> 3. [Simply Optimized](https://modrinth.com/modpack/sop) - сборка для оптимизации
> 4. [Double Doors](https://modrinth.com/mod/double-doors) - двойные двери открываются одним кликом
> 5. [Falling Tree](https://modrinth.com/mod/fallingtree) - название само за себя говорит

<hr>

> **локальные**
> 1.  [Litematica](https://modrinth.com/mod/litematica) - 3Д проекции построек
> 2. [FreeCam](https://modrinth.com/mod/freecam) -  specator mode
> 3. [BetterF3](https://modrinth.com/mod/better-f3) и [MiniHUD](https://modrinth.com/mod/minihud) - убирает юзлесс инфу из F3
> 4. [ClickThrough](https://modrinth.com/mod/clickthrough+) - проклик через таблички/фреймы
> 5. [Mouse Tweaks](https://modrinth.com/mod/mouse-tweaks) - сами почитайте хз
> 6. [Peek](https://modrinth.com/mod/peek) - показывает содержимое шалкеров и т.д.

<hr>

_***[Назад к содержанию](#contents)***_
