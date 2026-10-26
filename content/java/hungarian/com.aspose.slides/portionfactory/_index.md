---
title: PortionFactory
second_title: Aspose.Slides Java API Referenciája
description: Lehetővé teszi teszt részletek létrehozását
type: docs
url: /hu/com.aspose.slides/portionfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Lehetővé teszi teszt részletek létrehozását

--------------------

COM kompatibilitásért
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Üres szövegrészt hoz létre.

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


A megadott karakterláncból szövegrészt hoz létre.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | String. |

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Megadott részletadatok felhasználásával hoz létre egy részt.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | A használni kívánt részlet. |

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion) - Portion.