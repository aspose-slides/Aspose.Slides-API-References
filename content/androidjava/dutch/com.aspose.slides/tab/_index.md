---
title: Tab
second_title: Aspose.Slides voor Android via Java API-referentie
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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Maakt een nieuwe Tab |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Retourneert of stelt de positie van een tabblad in. |
| [setPosition(double value)](#setPosition-double-) | Retourneert of stelt de positie van een tabblad in. |
| [getAlignment()](#getAlignment--) | Retourneert of stelt de uitlijningsstijl van een tabblad in. |
| [setAlignment(int value)](#setAlignment-int-) | Retourneert of stelt de uitlijningsstijl van een tabblad in. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Vergelijkt het huidige exemplaar met een ander object van hetzelfde type. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


Maakt een nieuwe Tab

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | double | Positie van het tabblad. |
| align | int | Uitlijning. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


Retourneert of stelt de positie van een tabblad in. Het toewijzen van deze eigenschap kan de index van het tabblad in de collectie wijzigen en de enumerator ongeldig maken. Lezen/schrijven double.

**Retour:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


Retourneert of stelt de positie van een tabblad in. Het toewijzen van deze eigenschap kan de index van het tabblad in de collectie wijzigen en de enumerator ongeldig maken. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Retourneert of stelt de uitlijningsstijl van een tabblad in. Lezen/schrijven [TabAlignment](../../com.aspose.slides/tabalignment).

**Retour:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Retourneert of stelt de uitlijningsstijl van een tabblad in. Lezen/schrijven [TabAlignment](../../com.aspose.slides/tabalignment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Vergelijkt het huidige exemplaar met een ander object van hetzelfde type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een object om te vergelijken met dit exemplaar. |

**Retour:**
int - Een 32-bits integer die de relatieve volgorde van de vergelijkbare objecten aangeeft. De teruggegeven waarde heeft de volgende betekenissen:

 * < 0 - Dit exemplaar is kleiner dan obj.
 * = 0 - Dit exemplaar is gelijk aan obj.
 * > 0 - Dit exemplaar is groter dan obj.