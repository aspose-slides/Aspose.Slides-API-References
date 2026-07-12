---
title: Tab
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Tabulator-Tabellierung für einen Text dar.
type: docs
url: /de/com.aspose.slides/tab/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Stellt eine Tabulator-Tabellierung für einen Text dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Erstellt neuen Tab |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Gibt die Position eines Tabs zurück oder legt sie fest. |
| [setPosition(double value)](#setPosition-double-) | Gibt die Position eines Tabs zurück oder legt sie fest. |
| [getAlignment()](#getAlignment--) | Gibt den Ausrichtungsstil eines Tabs zurück oder legt ihn fest. |
| [setAlignment(int value)](#setAlignment-int-) | Gibt den Ausrichtungsstil eines Tabs zurück oder legt ihn fest. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Erstellt einen neuen Tab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | double | Tab-Position. |
| align | int | Ausrichtung. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbarer long.

**Rückgabewert:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Gibt die Position eines Tabs zurück oder legt sie fest. Das Zuweisen dieser Eigenschaft kann den Index des Tabs in der Sammlung ändern und den Enumerator ungültig machen. Lesen/Schreiben double.

**Rückgabewert:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Gibt die Position eines Tabs zurück oder legt sie fest. Das Zuweisen dieser Eigenschaft kann den Index des Tabs in der Sammlung ändern und den Enumerator ungültig machen. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Gibt den Ausrichtungsstil eines Tabs zurück oder legt ihn fest. Lesen/Schreiben [TabAlignment](../../com.aspose.slides/tabalignment).

**Rückgabewert:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Gibt den Ausrichtungsstil eines Tabs zurück oder legt ihn fest. Lesen/Schreiben [TabAlignment](../../com.aspose.slides/tabalignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein Objekt zum Vergleich mit dieser Instanz. |

**Rückgabewert:**
int - Eine 32-Bit-Ganzzahl, die die relative Reihenfolge der Vergleichselemente angibt. Der Rückgabewert hat diese Bedeutungen: 

 *  < 0 - Diese Instanz ist kleiner als obj.
 *  = 0 - Diese Instanz ist gleich obj.
 *  > 0 - Diese Instanz ist größer als obj.