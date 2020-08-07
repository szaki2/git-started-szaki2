Projects are:

1.  **Time tracking system 1.**

A tool for a company, where users (employees of the company) can log how much
did they work on different tasks, while they were on-site in the office. All
employees have a dedicated computer.

Sima natív alkalmazás (Megmutatom Excelt )

Legolcsóbban valami egyszerű alkalmazással lehet megcsinálni.

Webre nincs szükség helyben lehet tárolni az adatokat és nem is írhatja felül
véletlen őket senki.

1.  **Time tracking system 2.**

A tool for a company, where users (employees of the company) can log how much
did they work on different tasks, while they were either on- or off-site (either
at home office, or at clients). You can safely assume that they have internet
access at all times.

Onepage web app

Egyszerű feladat, de számtalan helyről kellene begyűjteni adatokat. Mobil app
készítése túl költséges és felesleges. Weboldal egyszerű és csak megjelenítést
kell megoldani különböző eszközökön különböző css el.

1.  **Precision agriculture sensor system**

A farmer wants to know the humidity on each acres of her farm which is a
contiguous area of one km\^2. She would like to see the measurements on her
ipad.

Nagy írás bírású adatbázis, ha valós időben kellene rögzíteni Mongodb (sensorok
folyamatosan írni fogják) és egy ipadra optimalizált megjelenítő kliens miatt
natív app. onepage weboldal amit kifejezetten ipadre optimalizálunk szintén jó
lehet és olcsóbb. (Leírások szerint bonyolultabb ábrákhoz kimutatásokhoz natív
app ajánlott, miért?)

1.  **A 3D-heavy FPS game**

A 3D-heavy, single player FPS game, where your goal is to kill the unicorn king.

Natív kliens nyilván, unreal vagy unity

Ki kell használni minden kisajtolható erőforrást a gépből. Ezért csak natív
alkalmazás jöhet szóba.

1.  **Notes app**

Software which is capable of saving your notes while you're on the go. It should
be able to process speech to text, and hand drawing.

When it comes online, it should be able to sync your notes across all your
devices.

Google keep, Microsoft Notes. Ha fejleszteni kell akkor egy nem relációs
dokumentum tárolásra jó adatbázis? Mongodb? Natív appokkal gyors indulás kézírás
stb miatt. Lokálisan is less egy cachelt példány, amit felküld amint net van

1.  **Smart mirror**

An augmented reality application, with what you can try on virtually designed
clothes and jewelry.

Natív app ai funkciók speciális érzékelők és teljesítmény miatt. Adatbázis
szerveren tárolva a cuccok, amiket le tud húzni, illetve párat tárolhat is
(utoljára nézett x darab, legyakoribb kérések)

1.  **A blog**

A blog which can be edited from any device (given the right screen size, and the
adequate peripherals) on-line.

PWA Mögötte sima weboldal van mongodbvel Elvileg css el megfelelően lehet
különböző form faktorokra optimalizálni.

1.  **Mobile version of an existing marketplace**

There's an online marketplace, built using PHP, with millions of products, a
plethora of shopping and delivery modes, and it is being developed for 10 years.
Now the management wants to build a mobile version.

PWA ne kelljen átlapátolni meglévő hatalmas adatbázist és két külön csapatot
fentartani.

## Nehézség:

FPS

Bonyolult évekig tartó fejlesztés, nagyon sok résztvevővel.

Smart mirror

AR a ruhák emberekre illesztése miatt sok sok bonyodalomra számítok

Existing marketplace move to mobile

A régi php rendszer, ami 10 éves sok rejtett bombát rejthet

Notes app

Viszonylag bonyolult lehet az ütközések, illetve a syncronizációs hibák,
kézírásfelismerés miatt.

Blog

Sok különböző eszközre kell optimalizálni telefontól pc kig

Time tracking system 2

Viszonylag egyszerű program, de még is szerver kell hozzá míg 1. höz nem.

Time tracking system 1

Bárki, aki tud programozni meg tudja csinálni viszonylag hamar és csak aztán
derül ki, hogy borzasztó.
