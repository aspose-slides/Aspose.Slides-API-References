---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math border box
type: docs
url: /tr/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Bir matematik kenarlık kutusu oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Eleman üzerine uygulayarak bir matematik kenarlık kutusu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | kenarlık kutusunu uygulamak için matematik öğesi |

**Döndürür:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - yeni kenarlık kutusu öğesi
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Eleman üzerine uygulayarak bir matematik kenarlık kutusu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | kenarlık kutusunu uygulamak için matematik öğesi |
| hideTop | boolean | Üst Kenarı Gizle |
| hideBottom | boolean | Alt Kenarı Gizle |
| hideLeft | boolean | Sol Kenarı Gizle |
| hideRight | boolean | Sağ Kenarı Gizle |
| strikethroughHorizontal | boolean | Kenar Kutusu Üzeri Yatay Çizgi |
| strikethroughVertical | boolean | Kenar Kutusu Üzeri Dikey Çizgi |
| strikethroughBottomLeftToTopRight | boolean | Kenar Kutusu Altsoldan Üstsağa Çizgi |
| strikethroughTopLeftToBottomRight | boolean | Kenar Kutusu Üstsoldan Altsağa Çizgi |

**Döndürür:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - yeni kenarlık kutusu öğesi