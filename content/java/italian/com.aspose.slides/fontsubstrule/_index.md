---
title: FontSubstRule
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le informazioni di sostituzione dei font
type: docs
url: /it/com.aspose.slides/fontsubstrule/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Rappresenta le informazioni di sostituzione dei font
## Costruttori

| Constructor | Description |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Crea una nuova istanza. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Crea una nuova istanza. |
## Metodi

| Method | Description |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Font da sostituire. |
| [getDestFont()](#getDestFont--) | Font da utilizzare per la sostituzione. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regola da applicare per la sostituzione. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Crea una nuova istanza.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di origine. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di destinazione. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Crea una nuova istanza.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di origine. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di destinazione. |
| fontSubstRule | int | Regola di sostituzione del font. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Font da sostituire. Sola lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Font da utilizzare per la sostituzione. Sola lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Regola da applicare per la sostituzione. Sola lettura [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Restituisce:**
int