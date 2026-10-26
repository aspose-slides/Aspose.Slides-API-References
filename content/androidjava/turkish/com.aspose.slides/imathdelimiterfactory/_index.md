---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math delimiter
type: docs
url: /tr/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Bir matematik sınırlayıcı oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Elemanı uygulayarak bir matematik sınırlayıcı oluşturur |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Elemanı uygulayarak bir matematik sınırlayıcı oluşturur |
### createMathDelimiter(IMMathElement element) {#createMathDelimiter-com.aspose.slides.IMMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```


Elemanı uygulayarak bir matematik sınırlayıcı oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | sınırlayıcı uygulanacak matematik öğesi |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - yeni matematik sınırlayıcı
### createMathDelimiter(IMMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


Elemanı uygulayarak bir matematik sınırlayıcı oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | sınırlayıcı uygulanacak matematik öğeleri |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - yeni matematik sınırlayıcı