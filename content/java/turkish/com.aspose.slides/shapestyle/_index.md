---
title: ShapeStyle
second_title: Aspose.Slides için Java API Referansı
description: Şekillerin stil referansını temsil eder.
type: docs
url: /tr/com.aspose.slides/shapestyle/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

Şeklin stil referansını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLineColor()](#getLineColor--) | Şeklin dış çizgi rengini döndürür. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Stil matrisindeki çizginin sütun dizinini döndürür veya ayarlar. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Stil matrisindeki çizginin sütun dizinini döndürür veya ayarlar. |
| [getFillColor()](#getFillColor--) | Şeklin dolgu rengini döndürür. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Stil matrislerindeki şeklin dolgu sütun dizinini döndürür veya ayarlar. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Stil matrislerindeki şeklin dolgu sütun dizinini döndürür veya ayarlar. |
| [getEffectColor()](#getEffectColor--) | Şeklin efekt rengini döndürür. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Stil matrisindeki şeklin efekt sütun dizinini döndürür veya ayarlar. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Stil matrisindeki şeklin efekt sütun dizinini döndürür veya ayarlar. |
| [getFontColor()](#getFontColor--) | Şeklin yazı tipi rengini döndürür. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Yazı tipi koleksiyonundaki şeklin yazı tipi dizinini döndürür veya ayarlar. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Yazı tipi koleksiyonundaki şeklin yazı tipi dizinini döndürür veya ayarlar. |
### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

Şeklin dış çizgi rengini döndürür. Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

Stil matrisindeki çizginin sütun dizinini döndürür veya ayarlar. Okuma/yazma int.

**Döndürür:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

Stil matrisindeki çizginin sütun dizinini döndürür veya ayarlar. Okuma/yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

Şeklin dolgu rengini döndürür. Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

Stil matrislerindeki şeklin dolgu sütun dizinini döndürür veya ayarlar. 0, dolgu yok demektir, pozitif değer - temanın dolgu stillerindeki dizin, negatif değer - temanın arka plan stillerindeki dizin. Okuma/yazma short.

**Döndürür:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

Stil matrislerindeki şeklin dolgu sütun dizinini döndürür veya ayarlar. 0, dolgu yok demektir, pozitif değer - temanın dolgu stillerindeki dizin, negatif değer - temanın arka plan stillerindeki dizin. Okuma/yazma short.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

Şeklin efekt rengini döndürür. Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

Stil matrisindeki şeklin efekt sütun dizinini döndürür veya ayarlar. Okuma/yazma long.

**Döndürür:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

Stil matrisindeki şeklin efekt sütun dizinini döndürür veya ayarlar. Okuma/yazma long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

Şeklin yazı tipi rengini döndürür. Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

Yazı tipi koleksiyonundaki şeklin yazı tipi dizinini döndürür veya ayarlar. Okuma/yazma [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Döndürür:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

Yazı tipi koleksiyonundaki şeklin yazı tipi dizinini döndürür veya ayarlar. Okuma/yazma [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |