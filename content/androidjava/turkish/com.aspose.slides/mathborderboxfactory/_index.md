---
title: MathBorderBoxFactory
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Matematik sınır kutusu oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/mathborderboxfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Matematik sınır kutusu oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Eleman üzerine uygulanarak bir matematik sınır kutusu oluşturur |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Eleman üzerine uygulanarak bir matematik sınır kutusu oluşturur |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Eleman üzerine uygulanarak bir matematik sınır kutusu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | sınır kutusu uygulanacak matematik öğesi |

**Dönüş Değeri:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - yeni sınır kutusu öğesi
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Eleman üzerine uygulanarak bir matematik sınır kutusu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | sınır kutusu uygulanacak matematik öğesi |
| hideTop | boolean | Üst Kenarı Gizle |
| hideBottom | boolean | Alt Kenarı Gizle |
| hideLeft | boolean | Sol Kenarı Gizle |
| hideRight | boolean | Sağ Kenarı Gizle |
| strikethroughHorizontal | boolean | Sınır Kutusu Yatay Çizgi |
| strikethroughVertical | boolean | Sınır Kutusu Dikey Çizgi |
| strikethroughBottomLeftToTopRight | boolean | Sınır Kutusu Alt Sol'den Üst Sağ'a Çizgi |
| strikethroughTopLeftToBottomRight | boolean | Sınır Kutusu Üst Sol'den Alt Sağ'a Çizgi |

**Dönüş Değeri:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - yeni sınır kutusu öğesi