---
title: ColorOperation
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar olika färgoperationer som används för färgtransformeringar.
type: docs
url: /sv/com.aspose.slides/coloroperation/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Representerar olika färgoperationer som används för färgtransformeringar. Oföränderligt objekt.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Skapar en ny färgtransformationsoperation. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Skapar en ny färgtransformationsoperation. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOperationType()](#getOperationType--) | Returnerar eller sätter typen av en operation. |
| [getParameter()](#getParameter--) | Returnerar en parameter för en operation. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om de två ColorOperation-instanserna är lika. |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ, lämplig för användning i hashalgoritmer och datastrukturer såsom en hash-tabell. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Skapar en ny färgtransformationsoperation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| op | int | Operationstyp. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Skapar en ny färgtransformationsoperation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| op | int | Operationstyp. |
| parameter | float | Operationsparameter. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Returnerar eller sätter typen av en operation. Skrivskyddad [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Returnerar:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Returnerar en parameter för en operation. Skrivskyddad float.

**Returnerar:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om de två ColorOperation-instanserna är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation att jämföra med den aktuella ColorOperation. |

**Returnerar:**
boolean - **true** om den angivna ColorOperation är lika med den aktuella ColorOperation; annars, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hashfunktion för en viss typ, lämplig för användning i hashalgoritmer och datastrukturer såsom en hash-tabell.

**Returnerar:**
int