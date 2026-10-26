---
title: IFontSubstRule
second_title: Aspose.Slides Android számára Java API-referencia
description: A betűkészlet helyettesítési információkat reprezentál
type: docs
url: /hu/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

A betűkészlet helyettesítési információkat reprezentál
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | A helyettesítendő betűkészlet Csak olvasható [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | A helyettesítéshez használandó betűkészlet Csak olvasható [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | A helyettesítéshez alkalmazandó szabály Csak olvasható [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```


A helyettesítendő betűkészlet Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```


A helyettesítéshez használandó betűkészlet Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```


A helyettesítéshez alkalmazandó szabály Csak olvasható [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Returns:**
int