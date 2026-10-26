---
title: FontSubstRule
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt informatie over lettertypevervanging voor
type: docs
url: /nl/com.aspose.slides/fontsubstrule/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Stelt informatie over lettertypevervanging voor
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Maakt een nieuw exemplaar. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Maakt een nieuw exemplaar. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Lettertype om te vervangen. |
| [getDestFont()](#getDestFont--) | Lettertype te gebruiken voor vervanging. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regel die moet worden toegepast voor vervanging. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Maakt een nieuw exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Bronlettertype. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Doellettertype. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Maakt een nieuw exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Bronlettertype. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Doellettertype. |
| fontSubstRule | int | Font subst rule. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Lettertype om te vervangen. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Retourwaarden:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Lettertype te gebruiken voor vervanging. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Retourwaarden:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Regel die moet worden toegepast voor vervanging. Alleen-lezen [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Retourwaarden:**
int