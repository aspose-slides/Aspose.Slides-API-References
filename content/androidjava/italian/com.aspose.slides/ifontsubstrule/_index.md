---
title: IFontSubstRule
second_title: Aspose.Slides per Android via Java API Reference
description: Rappresenta le informazioni di sostituzione del font
type: docs
url: /it/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

Rappresenta le informazioni di sostituzione del font
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Font da sostituire Solo lettura [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | Font da usare per la sostituzione Solo lettura [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regola da applicare per la sostituzione Solo lettura [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```


Font da sostituire Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```


Font da usare per la sostituzione Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```


Regola da applicare per la sostituzione Solo lettura [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Restituisce:**
int