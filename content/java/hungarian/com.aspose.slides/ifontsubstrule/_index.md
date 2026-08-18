---
title: IFontSubstRule
second_title: Aspose.Slides for Java API Referencia
description: A betűtípus helyettesítési információkat képviseli
type: docs
url: /hu/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

A betűtípus helyettesítési információkat képviseli
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | A helyettesítendő betűtípus csak olvasható [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | A helyettesítéshez használandó betűtípus csak olvasható [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | A helyettesítésre alkalmazandó szabály csak olvasható [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```

A helyettesítendő betűtípus csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```

A helyettesítéshez használandó betűtípus csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```

A helyettesítésre alkalmazandó szabály csak olvasható [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Visszatér:**
int