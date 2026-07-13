---
title: FontSubstRule
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili informasi substitusi font
type: docs
url: /id/com.aspose.slides/fontsubstrule/
---
**Pewarisan:** 
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:** 
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Mewakili informasi substitusi font
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Membuat instance baru. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Membuat instance baru. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Font yang akan disubstitusi. |
| [getDestFont()](#getDestFont--) | Font yang digunakan untuk substitusi. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Aturan yang diterapkan untuk substitusi. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Membuat instance baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font sumber. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font tujuan. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Membuat instance baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font sumber. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font tujuan. |
| fontSubstRule | int | Aturan substitusi font. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Font yang akan disubstitusi. Baca-saja [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Font yang digunakan untuk substitusi. Baca-saja [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Aturan yang diterapkan untuk substitusi. Baca-saja [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Mengembalikan:**
int