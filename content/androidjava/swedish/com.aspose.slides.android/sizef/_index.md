---
title: SizeF
second_title: Aspose.Slides för Android via Java API-referens
description: Klass för att beskriva bredd- och höjddimensioner i någon godtycklig enhet med flyttalsvärden.
type: docs
url: /sv/com.aspose.slides.android/sizef/
---
**Arv:**
java.lang.Object
```
public class SizeF
```

Klass för att beskriva bredd- och höjddimensioner i någon godtycklig enhet med flyttalsvärden.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Skapa en ny SizeF-instans. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Hämta bredden på storleken. |
| [getHeight()](#getHeight--) | Hämta höjden på storleken. |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollera om denna storlek är lika med en annan storlek. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Returnera storleken som en sträng med formatet "WxH" |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

Skapa en ny SizeF-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | float | Bredden på storleken |
| height | float | Höjden på storleken |

### getWidth() {#getWidth--}
```
public float getWidth()
```

Hämta bredden på storleken.

**Returnerar:**
float - bredd
### getHeight() {#getHeight--}
```
public float getHeight()
```

Hämta höjden på storleken.

**Returnerar:**
float - höjd
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Kontrollera om denna storlek är lika med en annan storlek.

Två storlekar är lika om och endast om både deras bredder och höjder är lika.

För detta ändamål betraktas bredd-/höjdflyttalsvärdena som lika om och endast om metoden Float#floatToIntBits(float).floatToIntBits(float) returnerar identiskt int-värde när den appliceras på varje.

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

Returnera storleken som en sträng med formatet "WxH"

**Returnerar:**
java.lang.String - strängrepresentation av storleken