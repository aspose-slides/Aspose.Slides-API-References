---
title: FontSubstRule
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje informace o náhradě písma
type: docs
url: /cs/com.aspose.slides/fontsubstrule/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Reprezentuje informace o náhradě písma
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Vytvoří novou instanci. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Vytvoří novou instanci. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Písmo k nahrazení. |
| [getDestFont()](#getDestFont--) | Písmo použité pro nahrazení. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Pravidlo použité pro nahrazení. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Vytvoří novou instanci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Zdrojové písmo. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cílové písmo. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Vytvoří novou instanci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Zdrojové písmo. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cílové písmo. |
| fontSubstRule | int | Pravidlo nahrazení písma. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Písmo k nahrazení. Pouze ke čtení [IFontData](../../com.aspose.slides/ifontdata).

**Návratová hodnota:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Písmo použité pro nahrazení. Pouze ke čtení [IFontData](../../com.aspose.slides/ifontdata).

**Návratová hodnota:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Pravidlo použité pro nahrazení. Pouze ke čtení [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Návratová hodnota:**
int