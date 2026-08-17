---
title: IMathBarFactory
second_title: Aspose.Slides için Java API Referansı
description: Matematik çubuğu oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Matematik çubuğu oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Eleman üzerine uygulayarak bir matematik çubuğu oluşturur |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Eleman üzerine uygulayarak bir matematik çubuğu oluşturur |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```


Eleman üzerine uygulayarak bir matematik çubuğu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | çubuğu uygulamak için matematik öğesi |

**Döndürür:**
[IMathBar](../../com.aspose.slides/imathbar) - yeni matematik çubuğu öğesi
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```


Eleman üzerine uygulayarak bir matematik çubuğu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | çubuğu uygulamak için matematik öğesi |
| position | int | Çubuğun konumu |

**Döndürür:**
[IMathBar](../../com.aspose.slides/imathbar) - yeni matematik çubuğu öğesi