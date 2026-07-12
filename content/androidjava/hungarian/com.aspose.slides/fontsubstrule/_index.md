---
title: FontSubstRule
second_title: Aspose.Slides Androidhoz Java API hivatkozással
description: Betűtípuscsere információt képvisel
type: docs
url: /hu/com.aspose.slides/fontsubstrule/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

A betűtípuscsere információt képviseli
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Új példányt hoz létre. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Új példányt hoz létre. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Kicserélendő betűtípus. |
| [getDestFont()](#getDestFont--) | A helyettesítéshez használt betűtípus. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | A helyettesítésre alkalmazandó szabály. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Új példányt hoz létre.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Forrás betűtípus. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cél betűtípus. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Új példányt hoz létre.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Forrás betűtípus. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cél betűtípus. |
| fontSubstRule | int | Betűtípus-helyettesítési szabály. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Kicserélendő betűtípus. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


A helyettesítéshez használt betűtípus. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


A helyettesítésre alkalmazandó szabály. Csak olvasható [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Visszatérési érték:**
int