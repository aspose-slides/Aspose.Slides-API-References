---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /hu/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Megváltoztathatatlan objektum, amely a hatékony minta kitöltés tulajdonságait tartalmazza.

--------------------

Ez a felület a [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) és a [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) részeként használható.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Visszaadja a mintastílust. |
| [getForeColor()](#getForeColor--) | Visszaadja az előtér mintaszínt. |
| [getBackColor()](#getBackColor--) | Visszaadja a háttér mintaszínt. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Létrehoz egy csempe képet a minta kitöltéshez megadott színekkel. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Visszaadja a mintastílust. Csak olvasható [PatternStyle](../../com.aspose.slides/patternstyle).

**Visszaadja:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


Visszaadja az előtér mintaszínt. Csak olvasható java.awt.Color.

**Visszaadja:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


Visszaadja a háttér mintaszínt. Csak olvasható java.awt.Color.

**Visszaadja:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


Létrehoz egy csempe képet a minta kitöltéshez megadott színekkel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| background | java.awt.Color | A háttér java.awt.Color a mintához. |
| foreground | java.awt.Color | Az előtér java.awt.Color a mintához. |

**Visszaadja:**
[IImage](../../com.aspose.slides/iimage) - Csempe [IImage](../../com.aspose.slides/iimage).