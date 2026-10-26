---
title: Metered
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Methoden zum Festlegen des gemessenen Schlüssels bereit.
type: docs
url: /de/com.aspose.slides/metered/
---
**Vererbung:**
java.lang.Object
```
public class Metered
```

Stellt Methoden zum Festlegen des gemessenen Schlüssels bereit.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Metered()](#Metered--) | Initialisiert eine neue Instanz dieser Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Setzt den gemessenen öffentlichen und privaten Schlüssel. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ruft die Größe der Verbrauchsdatei ab |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ruft das Verbrauchsguthaben ab |
| [isMeteredLicensed()](#isMeteredLicensed--) | Prüft, ob die gemessene Lizenz aktiviert ist |
### Metered() {#Metered--}
```
public Metered()
```


Initialisiert eine neue Instanz dieser Klasse.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Setzt den gemessenen öffentlichen und privaten Schlüssel. Wenn Sie eine gemessene Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Falls jedoch immer wieder das Hochladen von Verbrauchsdaten fehlschlägt und 24 Stunden überschreitet, wird die Lizenz in den Evaluierungsstatus gesetzt. Um diesen Fall zu vermeiden, sollten Sie regelmäßig den Lizenzstatus prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | java.lang.String | öffentlicher Schlüssel |
| privateKey | java.lang.String | privater Schlüssel |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Ruft die Größe der Verbrauchsdatei ab

**Rückgabe:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Ruft das Verbrauchsguthaben ab

**Rückgabe:**
double - Verbrauchsmenge
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Prüft, ob die gemessene Lizenz aktiviert ist

**Rückgabe:**
boolean - True oder false