---
title: IFontSubstRule
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje informacje o zamianie czcionek
type: docs
url: /pl/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

Reprezentuje informacje o zamianie czcionek
## Metody

| Metoda | Opis |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Czcionka do zastąpienia Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | Czcionka do użycia w zastąpieniu Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Reguła do zastosowania przy zastąpieniu Tylko do odczytu [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```


Czcionka do zastąpienia Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```


Czcionka do użycia w zastąpieniu Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```


Reguła do zastosowania przy zastąpieniu Tylko do odczytu [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Zwraca:**
int