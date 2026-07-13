---
title: Metered
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt methoden om de metered-sleutel in te stellen.
type: docs
url: /nl/com.aspose.slides/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Biedt methoden om de metered-sleutel in te stellen.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [Metered()](#Metered--) | Initialiseert een nieuwe instantie van deze klasse. |
## Methoden

| Method | Beschrijving |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Stelt de metered openbare en privésleutel in. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Haalt de bestandsgrootte van consumptie op |
| [getConsumptionCredit()](#getConsumptionCredit--) | Haalt het consumptietegoed op |
| [isMeteredLicensed()](#isMeteredLicensed--) | Controleer of metered is gelicentieerd |
### Metered() {#Metered--}
```
public Metered()
```


Initialiseert een nieuwe instantie van deze klasse.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Stelt de metered openbare en privésleutel in. Als u een metered-licentie aanschaft, moet deze API worden aangeroepen bij het starten van de toepassing; normaal is dat voldoende. Als het echter steeds lukt om consumptiegegevens niet te uploaden en de 24 uur overschrijdt, wordt de licentie op evaluatiestatus gezet. Om dit te voorkomen, dient u regelmatig de licentiestatus te controleren; is deze op evaluatie ingesteld, roep dan deze API opnieuw aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| publicKey | java.lang.String | openbare sleutel |
| privateKey | java.lang.String | privésleutel |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Haalt de bestandsgrootte van consumptie op

**Retourneert:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Haalt het consumptietegoed op

**Retourneert:**
double - consumptie-hoeveelheid
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Controleer of metered is gelicentieerd

**Retourneert:**
boolean - Waar of onwaar