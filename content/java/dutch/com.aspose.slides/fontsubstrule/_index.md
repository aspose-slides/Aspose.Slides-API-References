---
title: FontSubstRule
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt informatie over lettertypevervanging
type: docs
url: /nl/com.aspose.slides/fontsubstrule/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Representeert informatie over lettertypevervanging
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Maakt een nieuw exemplaar aan. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Maakt een nieuw exemplaar aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Lettertype om te vervangen. |
| [getDestFont()](#getDestFont--) | Lettertype dat voor vervanging wordt gebruikt. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regel die op vervanging wordt toegepast. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Maakt een nieuw exemplaar aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Bronlettertype. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Doellettertype. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Maakt een nieuw exemplaar aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Bronlettertype. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Doellettertype. |
| fontSubstRule | int | Lettertype vervangingsregel. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Lettertype om te vervangen. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Retourwaarde:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Lettertype dat voor vervanging wordt gebruikt. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Retourwaarde:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Regel die op vervanging wordt toegepast. Alleen-lezen [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Retourwaarde:**
int