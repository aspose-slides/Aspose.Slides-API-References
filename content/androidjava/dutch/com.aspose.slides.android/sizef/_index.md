---
title: SizeF
second_title: Aspose.Slides voor Android via Java API-referentie
description: Klasse voor het beschrijven van breedte- en hoogtedimensies in een willekeurige eenheid met drijvende-kommagetallen.
type: docs
url: /nl/com.aspose.slides.android/sizef/
---
**Erfenis:**
java.lang.Object
```
public class SizeF
```

Klasse voor het beschrijven van breedte- en hoogte-dimensies in een willekeurige eenheid met zwevende-kommagetallen.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Maak een nieuwe SizeF-instantie aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Haalt de breedte van de grootte op. |
| [getHeight()](#getHeight--) | Haalt de hoogte van de grootte op. |
| [equals(Object obj)](#equals-java.lang.Object-) | Controleert of deze grootte gelijk is aan een andere grootte. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Retourneert de grootte weergegeven als een string met het formaat "WxH" |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Maak een nieuwe SizeF-instantie aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | float | De breedte van de grootte |
| height | float | De hoogte van de grootte |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Haalt de breedte van de grootte op.

**Retour:**
float - width
### getHeight() {#getHeight--}
```
public float getHeight()
```


Haalt de hoogte van de grootte op.

**Retour:**
float - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Controleert of deze grootte gelijk is aan een andere grootte.

Twee groottes zijn gelijk als en slechts als zowel hun breedtes als hun hoogtes gelijk zijn.

Voor dit doel worden de breedte-/hoogte-floatwaarden als gelijk beschouwd als en slechts als de methode Float\#floatToIntBits(float).floatToIntBits(float) de identieke int waarde retourneert wanneer op elk ervan toegepast wordt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Retour:**
boolean -  true  als de objecten gelijk waren,  false  anders
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Retour:**
int
### toString() {#toString--}
```
public String toString()
```


Retourneert de grootte als een string met het formaat "WxH"

**Retour:**
java.lang.String - stringrepresentatie van de grootte