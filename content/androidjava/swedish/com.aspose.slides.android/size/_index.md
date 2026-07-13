---
title: Size
second_title: Aspose.Slides för Android via Java API-referens
description: Klass för att beskriva bredd- och höjddimensioner i någon godtycklig enhet.
type: docs
url: /sv/com.aspose.slides.android/size/
---
**Arv:**
java.lang.Object
```
public class Size
```

Klass för att beskriva bredd- och höjddimensioner i någon godtycklig enhet.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Skapa en ny Size-instans. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Hämta bredden på storleken. |
| [getHeight()](#getHeight--) | Hämta höjden på storleken. |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollera om den här storleken är lika med en annan storlek. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Returnera storleken som en sträng med formatet  "WxH"  |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Skapa en ny Size-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | Bredden på storleken |
| height | int | Höjden på storleken |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämta bredden på storleken.

**Returnerar:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämta höjden på storleken.

**Returnerar:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kontrollera om den här storleken är lika med en annan storlek.

Två storlekar är lika om och endast om både deras breddar och höjder är lika.

Ett size-objekt är aldrig lika med någon annan typ av objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returnerar:**
boolean -  true  om objekten var lika,  false  annars
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returnerar:**
int
### toString() {#toString--}
```
public String toString()
```


Returnera storleken som en sträng med formatet  "WxH" 

**Returnerar:**
java.lang.String - strängrepresentation av storleken