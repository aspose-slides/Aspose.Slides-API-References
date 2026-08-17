---
title: MathBorderBoxFactory
second_title: Aspose.Slides for Java API Referansı
description: Matematik kenarlık kutusu oluşturulmasına izin verir
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

Matematik kenarlık kutusu oluşturulmasına izin verir

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Elemanın üzerine uygulanarak bir matematik kenarlık kutusu oluşturur |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Elemanın üzerine uygulanarak bir matematik kenarlık kutusu oluşturur |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

Elemanın üzerine uygulanarak bir matematik kenarlık kutusu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | kenarlık kutusunu uygulamak için matematik öğesi |

**Dönüş Değeri:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - yeni kenarlık kutusu öğesi
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Elemanın üzerine uygulanarak bir matematik kenarlık kutusu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | kenarlık kutusunu uygulamak için matematik öğesi |
| hideTop | boolean | Üst Kenarı Gizle |
| hideBottom | boolean | Alt Kenarı Gizle |
| hideLeft | boolean | Sol Kenarı Gizle |
| hideRight | boolean | Sağ Kenarı Gizle |
| strikethroughHorizontal | boolean | Kenarlık Kutusu Yatay Üzeri Çizili |
| strikethroughVertical | boolean | Kenarlık Kutusu Dikey Üzeri Çizili |
| strikethroughBottomLeftToTopRight | boolean | Kenarlık Kutusu Alt Sol'dan Üst Sağa Çizgi |
| strikethroughTopLeftToBottomRight | boolean | Kenarlık Kutusu Üst Sol'dan Alt Sağa Çizgi |

**Dönüş Değeri:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - yeni kenarlık kutusu öğesi