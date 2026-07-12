---
title: ColorOperation
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt verschiedene Farboperationen dar, die für Farbtransformationen verwendet werden.
type: docs
url: /de/com.aspose.slides/coloroperation/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Stellt verschiedene Farboperationen dar, die für Farbtransformationen verwendet werden. Unveränderliches Objekt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Erstellt eine neue Farbtransformationsoperation. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Erstellt eine neue Farbtransformationsoperation. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOperationType()](#getOperationType--) | Gibt den Typ einer Operation zurück oder legt ihn fest. |
| [getParameter()](#getParameter--) | Gibt einen Parameter einer Operation zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob die beiden ColorOperation-Instanzen gleich sind. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ, geeignet für den Einsatz in Hashing-Algorithmen und Datenstrukturen wie einer Hashtabelle. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


Erstellt eine neue Farbtransformationsoperation.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| op | int | Operationstyp. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


Erstellt eine neue Farbtransformationsoperation.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| op | int | Operationstyp. |
| parameter | float | Operationsparameter. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```


Gibt den Typ einer Operation zurück oder legt ihn fest. Nur Lesezugriff [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Rückgabe:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```


Gibt einen Parameter einer Operation zurück. Nur Lesezugriff float.

**Rückgabe:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob die beiden ColorOperation-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Die ColorOperation zum Vergleich mit der aktuellen ColorOperation. |

**Rückgabe:**
boolean - **true** wenn die angegebene ColorOperation gleich der aktuellen ColorOperation ist; sonst **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hashfunktion für einen bestimmten Typ, geeignet für den Einsatz in Hashing-Algorithmen und Datenstrukturen wie einer Hashtabelle.

**Rückgabe:**
int