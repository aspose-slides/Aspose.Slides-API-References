---
title: Metered
second_title: Aspose.Slides for Android a Java API hivatkozásban
description: Metódusokat biztosít a mérő kulcs beállításához.
type: docs
url: /hu/com.aspose.slides/metered/
---
**Öröklés:**
java.lang.Object
```
public class Metered
```

Metódusokat biztosít a mérő kulcs beállításához.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Metered()](#Metered--) | Inicializál egy új példányt ebből az osztályból. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Beállítja a mérő nyilvános és privát kulcsot. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Lekéri a fogyasztási fájl méretét. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Lekéri a fogyasztási kreditet. |
| [isMeteredLicensed()](#isMeteredLicensed--) | Ellenőrzi, hogy a mérő licencelve van-e. |

### Metered() {#Metered--}
```
public Metered()
```

Inicializál egy új példányt ebből az osztályból.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Beállítja a mérő nyilvános és privát kulcsot. Ha mérő licencet vásárol, az alkalmazás indításakor ezt az API-t kell meghívni; általában ez elegendő. Azonban ha folyamatosan nem sikerül feltölteni a fogyasztási adatokat, és a 24 órát meghaladja, a licence értékelési állapotra lesz beállítva. Ennek elkerülése érdekében rendszeresen ellenőrizni kell a licenc állapotát; ha értékelési állapotban van, újra meg kell hívni ezt az API-t.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| publicKey | java.lang.String | nyilvános kulcs |
| privateKey | java.lang.String | privát kulcs |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Lekéri a fogyasztási fájl méretét.

**Visszatérési érték:**
double

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Lekéri a fogyasztási kreditet.

**Visszatérési érték:**
double - fogyasztási mennyiség

### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Ellenőrzi, hogy a mérő licencelt-e.

**Visszatérési érték:**
boolean - Igaz vagy Hamis