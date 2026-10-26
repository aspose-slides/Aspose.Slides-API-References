---
title: Metered
second_title: Aspose.Slides for Java API Referencia
description: Metriált kulcs beállításához metódusokat biztosít.
type: docs
url: /hu/com.aspose.slides/metered/
---
**Öröklődés:**
java.lang.Object
```
public class Metered
```

Metriált kulcs beállításához metódusokat biztosít.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Metered()](#Metered--) | Új példányt hoz létre ebből az osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Beállítja a metriált nyilvános és privát kulcsot. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Lekéri a fogyasztási fájl méretét |
| [getConsumptionCredit()](#getConsumptionCredit--) | Lekéri a fogyasztási kreditet |
| [isMeteredLicensed()](#isMeteredLicensed--) | Ellenőrzi, hogy a metered licencelt-e |
### Metered() {#Metered--}
```
public Metered()
```

Új példányt hoz létre ebből az osztályból.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Beállítja a metriált nyilvános és privát kulcsot. Ha metered licencet vásárol, az alkalmazás indításakor ezt az API-t kell meghívni, általában ez elegendő. Azonban ha folyamatosan sikertelen a fogyasztási adatok feltöltése és több mint 24 órát telik el, a licenc értékelési (evaluation) státuszra áll, ennek elkerülése érdekében rendszeresen ellenőrizni kell a licenc állapotát; ha értékelési státuszban van, újra meg kell hívni ezt az API-t.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| publicKey | java.lang.String | nyilvános kulcs |
| privateKey | java.lang.String | privát kulcs |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Lekéri a fogyasztási fájl méretét

**Visszatérési érték:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Lekéri a fogyasztási kreditet

**Visszatérési érték:**
double - fogyasztási mennyiség
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Ellenőrzi, hogy a metered licencelt-e

**Visszatérési érték:**
boolean - Igaz vagy hamis