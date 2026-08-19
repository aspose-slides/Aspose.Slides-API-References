---
title: Metered
second_title: Aspose.Slides för Java API-referens
description: Tillhandahåller metoder för att ställa in mätad nyckel.
type: docs
url: /sv/com.aspose.slides/metered/
---
**Arv:**
java.lang.Object
```
public class Metered
```

Tillhandahåller metoder för att ställa in mätad nyckel.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [Metered()](#Metered--) | Initierar en ny instans av denna klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ställer in mätad offentlig och privat nyckel. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Hämtar konsumtionsfilens storlek |
| [getConsumptionCredit()](#getConsumptionCredit--) | Hämtar konsumtionskredit |
| [isMeteredLicensed()](#isMeteredLicensed--) | Kontrollerar om mätad är licensierad |
### Metered() {#Metered--}
```
public Metered()
```


Initierar en ny instans av denna klass.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ställer in mätad offentlig och privat nyckel. Om du köper en mätt licens, bör detta API anropas när applikationen startas; normalt är detta tillräckligt. Men om uppladdning av konsumtionsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen; om den är i utvärderingsstatus, anropa detta API igen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | java.lang.String | offentlig nyckel |
| privateKey | java.lang.String | privat nyckel |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Hämtar konsumtionsfilens storlek

**Returnerar:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Hämtar konsumtionskredit

**Returnerar:**
double - konsumtionskvantitet
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Kontrollerar om mätad är licensierad

**Returnerar:**
boolean - Sant eller falskt