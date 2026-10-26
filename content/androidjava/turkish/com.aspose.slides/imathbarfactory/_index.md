---
title: IMathBarFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math bar
type: docs
url: /tr/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Bir matematik çubuğu oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Create a math bar by applying to the element |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Create a math bar by applying to the element |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

Elemanın üzerine uygulanarak bir matematik çubuğu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | çubuğu uygulamak için matematik öğesi |

**Dönüş Değeri:**
[IMathBar](../../com.aspose.slides/imathbar) - yeni matematik çubuğu öğesi
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

Elemanın üzerine uygulanarak bir matematik çubuğu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | çubuğu uygulamak için matematik öğesi |
| position | int | çubuğun konumu |

**Dönüş Değeri:**
[IMathBar](../../com.aspose.slides/imathbar) - yeni matematik çubuğu öğesi