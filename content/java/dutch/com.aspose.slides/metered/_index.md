---
title: Metered
second_title: Aspose.Slides voor Java API-referentie
description: Biedt methoden om de metered-sleutel in te stellen.
type: docs
url: /nl/com.aspose.slides/metered/
---
**Erfenis:**
java.lang.Object
```
public class Metered
```

Biedt methoden om de metered-sleutel in te stellen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Metered()](#Metered--) | Initialiseert een nieuw exemplaar van deze klasse. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Stelt de metered publieke en private sleutel in. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Haalt consumptiebestandsgrootte op |
| [getConsumptionCredit()](#getConsumptionCredit--) | Haalt consumptietegoed op |
| [isMeteredLicensed()](#isMeteredLicensed--) | Controleert of metered is gelicentieerd |
### Metered() {#Metered--}
```
public Metered()
```


Initialiseert een nieuw exemplaar van deze klasse.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Stelt de metered publieke en private sleutel in. Als u een metered-licentie aanschaft, moet deze API worden aangeroepen bij het starten van de applicatie; normaal gesproken is dat voldoende. Als het echter steeds mislukt om consumptiegegevens te uploaden en de 24-uur-limiet wordt overschreden, wordt de licentie op evaluatiestatus gezet. Om zo’n geval te voorkomen, dient u regelmatig de licentiestatus te controleren; als deze op evaluatiestatus staat, roept u deze API opnieuw aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| publicKey | java.lang.String | publieke sleutel |
| privateKey | java.lang.String | privésleutel |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Haalt consumptiebestandsgrootte op

**Retour:**  
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Haalt consumptietegoed op

**Retour:**  
double - consumptie hoeveelheid
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Controleert of metered is gelicentieerd

**Retour:**  
boolean - Waar of onwaar