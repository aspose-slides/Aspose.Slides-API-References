---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Referansı
description: Şekil stil referansını temsil eder.
type: docs
url: /tr/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Şeklin stil referansını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLineColor()](#getLineColor--) | Şeklin anahat rengini döndürür. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Satırın stil matrisindeki sütun indeksini döndürür veya ayarlar. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Satırın stil matrisindeki sütun indeksini döndürür veya ayarlar. |
| [getFillColor()](#getFillColor--) | Şeklin dolgu rengini döndürür. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Şeklin stil matrislerindeki dolgu sütun indeksini döndürür veya ayarlar. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Şeklin stil matrislerindeki dolgu sütun indeksini döndürür veya ayarlar. |
| [getEffectColor()](#getEffectColor--) | Şeklin efekt rengini döndürür. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Şeklin stil matrisindeki efekt sütun indeksini döndürür veya ayarlar. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Şeklin stil matrisindeki efekt sütun indeksini döndürür veya ayarlar. |
| [getFontColor()](#getFontColor--) | Şeklin yazı tipi rengini döndürür. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Şeklin yazı tipi koleksiyonundaki font indeksini döndürür veya ayarlar. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Şeklin yazı tipi koleksiyonundaki font indeksini döndürür veya ayarlar. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Şeklin anahat rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Satırın stil matrisindeki sütun indeksini döndürür veya ayarlar. Okunur/yazılır int.

**Döndürür:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Satırın stil matrisindeki sütun indeksini döndürür veya ayarlar. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Şeklin dolgu rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Şeklin stil matrislerindeki dolgu sütun indeksini döndürür veya ayarlar. 0 dolgu yok demektir, pozitif değer - temanın dolgu stillerindeki indeks, negatif değer - temanın arka plan stillerindeki indeks. Okunur/yazılır short.

**Döndürür:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Şeklin stil matrislerindeki dolgu sütun indeksini döndürür veya ayarlar. 0 dolgu yok demektir, pozitif değer - temanın dolgu stillerindeki indeks, negatif değer - temanın arka plan stillerindeki indeks. Okunur/yazılır short.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Şeklin efekt rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Şeklin stil matrisindeki efekt sütun indeksini döndürür veya ayarlar. Okunur/yazılır long.

**Döndürür:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Şeklin stil matrisindeki efekt sütun indeksini döndürür veya ayarlar. Okunur/yazılır long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Şeklin yazı tipi rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Şeklin yazı tipi koleksiyonundaki font indeksini döndürür veya ayarlar. Okunur/yazılır [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Döndürür:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Şeklin yazı tipi koleksiyonundaki font indeksini döndürür veya ayarlar. Okunur/yazılır [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |