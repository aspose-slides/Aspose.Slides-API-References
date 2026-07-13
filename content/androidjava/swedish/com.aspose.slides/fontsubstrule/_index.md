---
title: FontSubstRule
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar information om teckensnittssubstitution
type: docs
url: /sv/com.aspose.slides/fontsubstrule/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Representerar information om teckensnittssubstitution
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Skapar ny instans. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Skapar ny instans. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Teckensnitt att ersätta. |
| [getDestFont()](#getDestFont--) | Teckensnitt att använda för substitution. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regel att använda för substitution. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Skapar ny instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Källteckensnitt. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Måtteckensnitt. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Skapar ny instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Källteckensnitt. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Måtteckensnitt. |
| fontSubstRule | int | Teckensnittssubstitutionsregel. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Teckensnitt att ersätta. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Teckensnitt att använda för substitution. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Regel att använda för substitution. Skrivskyddad [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Returnerar:**
int