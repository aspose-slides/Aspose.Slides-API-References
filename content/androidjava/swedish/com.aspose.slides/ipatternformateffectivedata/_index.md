---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som innehåller effektiva egenskaper för mönsterfyllning.
type: docs
url: /sv/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Oföränderligt objekt som innehåller effektiva egenskaper för mönsterfyllning.

--------------------

Detta gränssnitt används som en del av [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) och [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returnerar mönsterstilen. |
| [getForeColor()](#getForeColor--) | Returnerar förgrundens mönsterfärg. |
| [getBackColor()](#getBackColor--) | Returnerar bakgrundens mönsterfärg. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Skapar en kakelbild för mönsterfyllning med angivna färger. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Returnerar mönsterstilen. Skrivskyddad [PatternStyle](../../com.aspose.slides/patternstyle).

**Returnerar:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


Returnerar förgrundens mönsterfärg. Skrivskyddad java.lang.Integer.

**Returnerar:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


Returnerar bakgrundens mönsterfärg. Skrivskyddad java.lang.Integer.

**Returnerar:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


Skapar en kakelbild för mönsterfyllning med angivna färger.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| background | java.lang.Integer | Den bakgrund java.lang.Integer för mönstret. |
| foreground | java.lang.Integer | Den förgrund java.lang.Integer för mönstret. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Kakel [IImage](../../com.aspose.slides/iimage).