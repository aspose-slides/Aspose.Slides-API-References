---
title: FontSubstRule
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje informacje o substytucji czcionki
type: docs
url: /pl/com.aspose.slides/fontsubstrule/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Reprezentuje informacje o substytucji czcionki
## Konstruktory

| Constructor | Description |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Tworzy nową instancję. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Tworzy nową instancję. |
## Metody

| Method | Description |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Czcionka do substytucji. |
| [getDestFont()](#getDestFont--) | Czcionka używana do substytucji. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Reguła stosowana do substytucji. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Tworzy nową instancję.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka źródłowa. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka docelowa. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Tworzy nową instancję.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka źródłowa. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka docelowa. |
| fontSubstRule | int | Reguła substytucji czcionki. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Czcionka do substytucji. Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Czcionka używana do substytucji. Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Reguła stosowana do substytucji. Tylko do odczytu [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Zwraca:**
int