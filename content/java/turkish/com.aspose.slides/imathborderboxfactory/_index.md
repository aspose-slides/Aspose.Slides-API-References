---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Referansı
description: Matematik kenarlık kutusu oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Matematik kenarlık kutusu oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Öğeye uygulayarak bir matematik kenarlık kutusu oluşturur |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Öğeye uygulayarak bir matematik kenarlık kutusu oluşturur |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Öğeye uygulayarak bir matematik kenarlık kutusu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | kenarlık kutusu uygulanacak matematik öğesi |

**Dönüş:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - yeni kenarlık kutusu öğesi
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Öğeye uygulayarak bir matematik kenarlık kutusu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | kenarlık kutusu uygulanacak matematik öğesi |
| hideTop | boolean | Üst Kenarı Gizle |
| hideBottom | boolean | Alt Kenarı Gizle |
| hideLeft | boolean | Sol Kenarı Gizle |
| hideRight | boolean | Sağ Kenarı Gizle |
| strikethroughHorizontal | boolean | Kenar Kutusu Üzerinde Yatay Çizgi |
| strikethroughVertical | boolean | Kenar Kutusu Üzerinde Dikey Çizgi |
| strikethroughBottomLeftToTopRight | boolean | Kenar Kutusu Alt Sol - Üst Sağ Çizgili |
| strikethroughTopLeftToBottomRight | boolean | Kenar Kutusu Üst Sol - Alt Sağ Çizgili |

**Dönüş:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - yeni kenarlık kutusu öğesi