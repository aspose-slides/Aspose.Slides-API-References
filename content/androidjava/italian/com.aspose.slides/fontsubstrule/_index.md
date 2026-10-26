---
title: FontSubstRule
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta le informazioni di sostituzione dei caratteri
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

Rappresenta le informazioni di sostituzione dei caratteri
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Crea una nuova istanza. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Crea una nuova istanza. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Font da sostituire. |
| [getDestFont()](#getDestFont--) | Font da usare per la sostituzione. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regola da applicare per la sostituzione. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

Crea una nuova istanza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di origine. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di destinazione. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

Crea una nuova istanza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di origine. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font di destinazione. |
| fontSubstRule | int | Regola di sostituzione del font. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

Font da sostituire. Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

Font da usare per la sostituzione. Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

Regola da applicare per la sostituzione. Solo lettura [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Restituisce:**
int