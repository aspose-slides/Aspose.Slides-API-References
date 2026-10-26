---
title: FontSubstRule
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje informacje o zamianie czcionek
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

Reprezentuje informacje o zamianie czcionek
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Tworzy nową instancję. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Tworzy nową instancję. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Czcionka do zamiany. |
| [getDestFont()](#getDestFont--) | Czcionka używana do zamiany. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Reguła stosowana przy zamianie. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

Tworzy nową instancję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka źródłowa. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka docelowa. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

Tworzy nową instancję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka źródłowa. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka docelowa. |
| fontSubstRule | int | Reguła zamiany czcionki. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

Czcionka do zamiany. Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

Czcionka używana do zamiany. Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

Reguła stosowana przy zamianie. Tylko do odczytu [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Zwraca:**
int