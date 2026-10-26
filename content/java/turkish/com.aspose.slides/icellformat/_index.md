---
title: ICellFormat
second_title: Aspose.Slides for Java API Referansı
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
| [getBorderLeft()](#getBorderLeft--) | Sol kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderTop()](#getBorderTop--) | Üst kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderRight()](#getBorderRight--) | Sağ kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderBottom()](#getBorderBottom--) | Alt kenar çizgi özellikleri nesnesi döndürür. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Sol-üstten sağ-alta köşegen çizgi özellikleri nesnesi döndürür. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Sol-alt-tan sağ-üst köşegen çizgi özellikleri nesnesi döndürür. |
| [getTransparency()](#getTransparency--) | Dolgu renginin şeffaflığını alır veya ayarlar. |
| [setTransparency(float value)](#setTransparency-float-) | Dolgu renginin şeffaflığını alır veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım ve tablo stilleri uygulanmış etkili tablo hücresi biçimlendirme özelliklerini alır. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Bir hücre dolgu özellikleri nesnesi döndürür. Sadece okuma [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Sol kenar çizgi özellikleri nesnesi döndürür. Sadece okuma [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Üst kenar çizgi özellikleri nesnesi döndürür. Sadece okuma [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Sağ kenar çizgi özellikleri nesnesi döndürür. Sadece okuma [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Alt kenar çizgi özellikleri nesnesi döndürür. Sadece okuma [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Sol-üstten sağ-alta köşegen çizgi özellikleri nesnesi döndürür. Sadece okuma [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Sol-alt-tan sağ-üst köşegen çizgi özellikleri nesnesi döndürür. Sadece okuma [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Dolgu renginin şeffaflığını alır veya ayarlar. Okuma/yazma  float .

**Döndürür:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Dolgu renginin şeffaflığını alır veya ayarlar. Okuma/yazma  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Kalıtım ve tablo stilleri uygulanmış etkili tablo hücresi biçimlendirme özelliklerini alır.

**Döndürür:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Bir [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).