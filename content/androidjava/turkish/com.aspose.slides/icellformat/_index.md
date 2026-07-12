---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Bir tablo hücresinin biçimini temsil eder.
type: docs
url: /tr/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Bir tablo hücresinin biçimini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Bir hücre dolgu özellikleri nesnesi döndürür. |
| [getBorderLeft()](#getBorderLeft--) | Bir sol kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderTop()](#getBorderTop--) | Bir üst kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderRight()](#getBorderRight--) | Bir sağ kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderBottom()](#getBorderBottom--) | Bir alt kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Üst-soldan alt-sağa çapraz çizgi özellikleri nesnesi döndürür. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Alt-soldan üst-sağa çapraz çizgi özellikleri nesnesi döndürür. |
| [getTransparency()](#getTransparency--) | Dolgu renginin şeffaflığını alır veya ayarlar. |
| [setTransparency(float value)](#setTransparency-float-) | Dolgu renginin şeffaflığını alır veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım ve tablo stilleri uygulanmış etkili tablo hücresi biçimlendirme özelliklerini alır. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Bir hücre dolgu özellikleri nesnesi döndürür. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Bir sol kenar çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Bir üst kenar çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Bir sağ kenar çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Bir alt kenar çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Üst-soldan alt-sağa çapraz çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Alt-soldan üst-sağa çapraz çizgi özellikleri nesnesi döndürür. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Dolgu renginin şeffaflığını alır veya ayarlar. Okunur/Yazılır  float .

**Döndürür:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Dolgu renginin şeffaflığını alır veya ayarlar. Okunur/Yazılır  float .

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Kalıtım ve tablo stilleri uygulanmış etkili tablo hücresi biçimlendirme özelliklerini alır.

**Döndürür:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Bir [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).