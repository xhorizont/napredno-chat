# Flutter Messenger Application

## Opis

Aplikaciji za klepet Flutter! Ta aplikacija omogoča uporabnikom nemoteno povezovanje in komunikacijo prek besedila in slik. Aplikacija je zgrajena z uporabo Flutterja za sprednji del in se integrira s Firebase za zaledne storitve, vključno s preverjanjem pristnosti, bazo podatkov v realnem času in shranjevanjem.

## Lastnosti

* Uporabniku prijazen vmesnik za intuitivno izkušnjo klepetanja.
* Preverjanje pristnosti Firebase s preverjanjem OTP za varne prijave.
* Sporočanje v realnem času z uporabo Firebase Realtime Database za takojšnjo dostavo sporočil.
* Integracija Firebase Storage za skupno rabo slik.
* Podpira platformi Android in iOS.

## Demo

<img src=demo.png/>

## Setup Instructions

Če želite uporabiti ta projekt, sledite tem korakom:

1. Klonirajte repozitorij v vaš lokalni računalnik: `git clone https://github.com/xhorizont/napredno-chat`
2. Nastavite Firebase:

* Ustvarite nov projekt Firebase v [konzoli Firebase](https://console.firebase.google.com/) .
* Omogočite avtentikacijo Firebase s preverjanjem OTP, zbirko podatkov Firebase v realnem času in shrambo Firebase za svoj projekt.
* Prenesite `google-services.json`datoteko iz Firebase in jo postavite v `android/app/`imenik tega projekta Flutter.

3. Namestite Flutter: zagotovite, da je Flutter nameščen na vaši napravi. Če ne, sledite navodilom na [uradnem spletnem mestu Flutter](https://flutter.dev/docs/get-started/install) , da ga nastavite.
4. Pridobi odvisnosti: Zaženite naslednji ukaz v imeniku projekta, da pridobite vse zahtevane odvisnosti:
5. Povežite se s Firebase: odprite `android/app/build.gradle`datoteko in se prepričajte, da so odvisnosti in konfiguracija Firebase pravilno nastavljene.
6. Zaženite aplikacijo: Povežite fizično napravo ali uporabite emulator, nato zaženite aplikacijo z naslednjim ukazom:
7. Preizkusite aplikacijo: preverite, ali preverjanje pristnosti Firebase, preverjanje OTP, baza podatkov v realnem času in shranjevanje slik delujejo, kot je predvideno. Preizkusite funkcionalnosti aplikacije s pošiljanjem in prejemanjem sporočil in slik.

## Odvisnosti

Za razvoj te aplikacije so bili uporabljeni naslednji paketi:

* [get: ^4.6.5](https://pub.dev/packages/get) : Knjižnica za upravljanje stanja za Flutter, ki poenostavi postopek upravljanja stanj aplikacije.
* [image_picker: ^1.0.1](https://pub.dev/packages/image_picker) : Omogoča uporabnikom, da izberejo slike in videoposnetke iz galerije ali kamere naprave.
* [firebase_core: ^2.4.1](https://pub.dev/packages/firebase_core) : Zagotavlja osnovno funkcionalnost Firebase in inicializacijo za aplikacije Flutter.
* [firebase_storage: ^11.0.10](https://pub.dev/packages/firebase_storage) : vtičnik Flutter za uporabo Firebase Cloud Storage, ki omogoča nalaganje in prenašanje datotek.
* [firebase_auth: ^4.2.5](https://pub.dev/packages/firebase_auth) : vtičnik Flutter za uporabo preverjanja pristnosti Firebase, ki omogoča enostavno preverjanje pristnosti uporabnika.
* [cloud_firestore: ^4.3.1](https://pub.dev/packages/cloud_firestore) : Vtičnik Flutter za uporabo Firebase Cloud Firestore, baze podatkov v oblaku NoSQL za shranjevanje in sinhronizacijo podatkov.
* [firebase_database: ^10.0.9](https://pub.dev/packages/firebase_database) : vtičnik Flutter za uporabo Firebase Realtime Database, ki zagotavlja bazo podatkov NoSQL, gostujočo v oblaku.
* [shared_preferences: ^2.2.0](https://pub.dev/packages/shared_preferences) : vtičnik Flutter za ohranitev podatkov ključ-vrednost v napravi.
* [path_provider: ^2.0.15](https://pub.dev/packages/path_provider) : Omogoča dostop do imenikov v datotečnem sistemu naprave.
* [animated_bottom_navigation_bar: ^1.2.0](https://pub.dev/packages/animated_bottom_navigation_bar) : Prilagodljiva animirana spodnja navigacijska vrstica za Flutter.
* [photo_view: ^0.14.0](https://pub.dev/packages/photo_view) : Zagotavlja možnosti povečave za ogled fotografij za Flutter.
* [cached_network_image: ^3.2.3](https://pub.dev/packages/cached_network_image) : Predpomni omrežne slike za izboljšanje zmogljivosti pri nalaganju slik iz interneta.
* [dio: ^5.3.0](https://pub.dev/packages/dio) : Zmogljiv odjemalec HTTP za Dart, ki podpira API-je RESTful, FormData in drugo.
* [intl: ^0.18.1](https://pub.dev/packages/intl) : Zagotavlja podporo za internacionalizacijo in lokalizacijo za aplikacije Flutter.

`pubspec.yaml` Preden zaženete aplikacijo, dodajte te odvisnosti v svojo datoteko.

## Težave

Če naletite na kakršne koli težave, preverite dokumentacijo projekta ali se obrnite na [repozitorij GitHub] za obstoječe težave in rešitve. Če potrebujete dodatno pomoč, lahko v repozitoriju izpostavite tudi nove težave.
