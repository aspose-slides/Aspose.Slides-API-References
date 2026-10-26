---
title: Size
second_title: Aspose.Slides voor Android via Java API-referentie
description: Klasse voor het beschrijven van breedte- en hoogte-dimensies in een willekeurige eenheid.
type: docs
url: /nl/com.aspose.slides.android/size/
---
**Overerving:**
java.lang.Object
```
public class Size
```

Klasse voor het beschrijven van breedte- en hoogtedimensies in een willekeurige eenheid.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Create a new Size instance. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Get the width of the size. |
| [getHeight()](#getHeight--) | Get the height of the size. |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if this size is equal to another size. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Return the size represented as a string with the format  "WxH"  |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

Maak een nieuw Size-object aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | De breedte van de grootte |
| height | int | De hoogte van de grootte |

### getWidth() {#getWidth--}
```
public int getWidth()
```

Haal de breedte van de grootte op.

**Retourwaarde:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```

Haal de hoogte van de grootte op.

**Retourwaarde:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Controleer of deze grootte gelijk is aan een andere grootte.

Twee groottes zijn gelijk indien en alleen indien zowel hun breedtes als hoogtes gelijk zijn.

Een grootte-object is nooit gelijk aan een ander type object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Retourwaarde:**
boolean -  true  als de objecten gelijk waren,  false  anders
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Retourwaarde:**
int
### toString() {#toString--}
```
public String toString()
```

Retourneer de grootte weergegeven als een tekenreeks met het formaat "WxH"

**Retourwaarde:**
java.lang.String - tekenreeksrepresentatie van de grootte