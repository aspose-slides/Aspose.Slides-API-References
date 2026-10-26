---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som innehåller effektiva mönsterfyllningsegenskaper.
type: docs
url: /sv/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Oföränderligt objekt som innehåller effektiva mönsterfyllningsegenskaper.

--------------------

Detta gränssnitt används som en del av [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) och [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returnerar mönsterstilen. |
| [getForeColor()](#getForeColor--) | Returnerar förgrundens mönsterfärg. |
| [getBackColor()](#getBackColor--) | Returnerar bakgrundens mönsterfärg. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Skapar en kakelbild för mönsterfyllning med angivna färger. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Returnerar mönsterstilen. Skrivskyddad [PatternStyle](../../com.aspose.slides/patternstyle).

**Returnerar:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


Returnerar förgrundens mönsterfärg. Skrivskyddad java.awt.Color.

**Returnerar:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


Returnerar bakgrundens mönsterfärg. Skrivskyddad java.awt.Color.

**Returnerar:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


Skapar en kakelbild för mönsterfyllning med angivna färger.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| background | java.awt.Color | Bakgrundens java.awt.Color för mönstret. |
| foreground | java.awt.Color | Förgrundens java.awt.Color för mönstret. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).