---
title: IFontSubstRule
second_title: Aspose.Slides for Java API Reference
description: Represents font subtituition information
type: docs
url: /sv/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

Representerar information om teckensnittsbyte
## Metoder

| Method | Description |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Teckensnitt att ersätta Endast läsning [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | Teckensnitt att använda för ersättning Endast läsning [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Regel att tillämpa för ersättning Endast läsning [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```


Teckensnitt att ersätta Endast läsning [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```


Teckensnitt att använda för ersättning Endast läsning [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```


Regel att tillämpa för ersättning Endast läsning [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Returnerar:**
int