---
title: Tab
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een tabulatie voor een tekst voor.
type: docs
url: /nl/com.aspose.slides/tab/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Stelt een tabulatie voor een tekst voor.
## Constructors

| Constructor | Description |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Maakt een nieuwe Tab aan |
## Methoden

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Retourneert of stelt de positie van een tab in. |
| [setPosition(double value)](#setPosition-double-) | Retourneert of stelt de positie van een tab in. |
| [getAlignment()](#getAlignment--) | Retourneert of stelt de uitlijningsstijl van een tab in. |
| [setAlignment(int value)](#setAlignment-int-) | Retourneert of stelt de uitlijningsstijl van een tab in. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Vergelijkt de huidige instantie met een ander object van hetzelfde type. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


Maakt een nieuwe Tab aan

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | double | Positie van de tab. |
| align | int | Uitlijning. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Returns:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


Retourneert of stelt de positie van een tab in. Het toewijzen van deze eigenschap kan de index van de tab in de collectie wijzigen en de enumerator ongeldig maken. Lezen/schrijven double.

**Returns:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


Retourneert of stelt de positie van een tab in. Het toewijzen van deze eigenschap kan de index van de tab in de collectie wijzigen en de enumerator ongeldig maken. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Retourneert of stelt de uitlijningsstijl van een tab in. Lezen/schrijven [TabAlignment](../../com.aspose.slides/tabalignment).

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Retourneert of stelt de uitlijningsstijl van een tab in. Lezen/schrijven [TabAlignment](../../com.aspose.slides/tabalignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Vergelijkt de huidige instantie met een ander object van hetzelfde type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Een object om te vergelijken met deze instantie. |

**Returns:**
int - Een 32-bit integer die de relatieve volgorde van de vergelijkende objecten aangeeft. De retourwaarde heeft de volgende betekenissen: 

 *  < 0 - Deze instantie is kleiner dan obj.
 *  = 0 - Deze instantie is gelijk aan obj.
 *  > 0 - Deze instantie is groter dan obj.