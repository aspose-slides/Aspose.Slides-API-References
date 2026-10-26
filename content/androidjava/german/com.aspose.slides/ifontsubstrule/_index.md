---
title: IFontSubstRule
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt Informationen zur Schriftart-Substitution dar
type: docs
url: /de/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

Stellt Informationen zur Schriftart-Substitution dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Schriftart zum Ersetzen, nur lesbar [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | Schriftart zur Verwendung für die Substitution, nur lesbar [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regel, die für die Substitution angewendet wird, nur lesbar [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```


Schriftart zum Ersetzen, nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```


Schriftart zur Verwendung für die Substitution, nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```


Regel, die für die Substitution angewendet wird, nur lesbar [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Rückgabe:**
int