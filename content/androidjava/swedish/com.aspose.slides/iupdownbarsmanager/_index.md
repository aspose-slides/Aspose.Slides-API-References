---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Tillhandahåller åtkomst till upp/ner staplar i linje- eller börsdiagram.
type: docs
url: /sv/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Tillhandahåller åtkomst till upp/ner staplar i linje- eller börsdiagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Returnerar formatet för upp staplarna. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Returnerar formatet för ner staplarna. |
| [hasUpDownBars()](#hasUpDownBars--) | Bestämmer om diagrammet har upp/ner staplar. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Bestämmer om diagrammet har upp/ner staplar. |
| [getGapWidth()](#getGapWidth--) | Returnerar eller anger gapbredd. |
| [setGapWidth(int value)](#setGapWidth-int-) | Returnerar eller anger gapbredd. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Returnerar formatet för upp staplarna. Endast läsning [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Returnerar formatet för ner staplarna. Endast läsning [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Bestämmer om diagrammet har upp/ner staplar. Läs/skriv boolean.

**Returnerar:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Bestämmer om diagrammet har upp/ner staplar. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Returnerar eller anger gapbredd. Läs/skriv int.

**Returnerar:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Returnerar eller anger gapbredd. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |