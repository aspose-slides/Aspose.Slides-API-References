---
title: Metered
second_title: Aspose.Slides für Java API Referenz
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
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Setzt den öffentlichen und privaten gemessenen Schlüssel. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Gibt die Größe der Verbrauchsdatei zurück |
| [getConsumptionCredit()](#getConsumptionCredit--) | Gibt das Verbrauchsguthaben zurück |
| [isMeteredLicensed()](#isMeteredLicensed--) | Prüft, ob das Metered lizenziert ist |
### Metered() {#Metered--}
```
public Metered()
```

Initialisiert eine neue Instanz dieser Klasse.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Setzt den öffentlichen und privaten gemessenen Schlüssel. Wenn Sie eine Metered-Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise ist das ausreichend. Wenn jedoch ständig das Hochladen der Verbrauchsdaten fehlschlägt und 24 Stunden überschritten werden, wird die Lizenz in den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig überprüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | java.lang.String | öffentlicher Schlüssel |
| privateKey | java.lang.String | privater Schlüssel |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Gibt die Größe der Verbrauchsdatei zurück

**Rückgabewert:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Gibt das Verbrauchsguthaben zurück

**Rückgabewert:**
double - Verbrauchsmenge
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Prüft, ob das Metered lizenziert ist

**Rückgabewert:**
boolean - Wahr oder falsch