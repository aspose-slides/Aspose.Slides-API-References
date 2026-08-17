---
title: IShapeStyle
second_title: Aspose.Slides for Java API Referansı
description: Şeklin stil referansını temsil eder.
type: docs
url: /tr/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Şeklin stil referansını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLineColor()](#getLineColor--) | Bir şeklin dış hat rengini döndürür. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Bir stil matrisinde satırın sütun indeksini döndürür veya ayarlar. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Bir stil matrisinde satırın sütun indeksini döndürür veya ayarlar. |
| [getFillColor()](#getFillColor--) | Bir şeklin dolgu rengini döndürür. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Bir stil matrisinde şeklin dolgu sütun indeksini döndürür veya ayarlar. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Bir stil matrisinde şeklin dolgu sütun indeksini döndürür veya ayarlar. |
| [getEffectColor()](#getEffectColor--) | Bir şeklin efekt rengini döndürür. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Bir stil matrisinde şeklin efekt sütun indeksini döndürür veya ayarlar. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Bir stil matrisinde şeklin efekt sütun indeksini döndürür veya ayarlar. |
| [getFontColor()](#getFontColor--) | Bir şeklin yazı tipi rengini döndürür. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Bir yazı tipi koleksiyonunda şeklin yazı tipi indeksini döndürür veya ayarlar. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Bir yazı tipi koleksiyonunda şeklin yazı tipi indeksini döndürür veya ayarlar. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Bir şeklin dış hat rengini döndürür. Yalnızca-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Bir stil matrisinde satırın sütun indeksini döndürür veya ayarlar. Okunur/yazılabilir int.

**Döndürür:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Bir stil matrisinde satırın sütun indeksini döndürür veya ayarlar. Okunur/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Bir şeklin dolgu rengini döndürür. Yalnızca-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Bir stil matrisinde şeklin dolgu sütun indeksini döndürür veya ayarlar. 0, dolgu olmadığını, pozitif değer tema dolgu stillerindeki indeksi, negatif değer tema arka plan stillerindeki indeksi ifade eder. Okunur/yazılabilir short.

**Döndürür:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Bir stil matrisinde şeklin dolgu sütun indeksini döndürür veya ayarlar. 0, dolgu olmadığını, pozitif değer tema dolgu stillerindeki indeksi, negatif değer tema arka plan stillerindeki indeksi ifade eder. Okunur/yazılabilir short.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Bir şeklin efekt rengini döndürür. Yalnızca-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Bir stil matrisinde şeklin efekt sütun indeksini döndürür veya ayarlar. Okunur/yazılabilir long.

**Döndürür:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Bir stil matrisinde şeklin efekt sütun indeksini döndürür veya ayarlar. Okunur/yazılabilir long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Bir şeklin yazı tipi rengini döndürür. Yalnızca-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Bir yazı tipi koleksiyonunda şeklin yazı tipi indeksini döndürür veya ayarlar. Okunur/yazılabilir [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Döndürür:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Bir yazı tipi koleksiyonunda şeklin yazı tipi indeksini döndürür veya ayarlar. Okunur/yazılabilir [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |