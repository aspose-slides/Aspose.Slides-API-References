---
title: IMathArrayFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math array
type: docs
url: /tr/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

Bir matematik dizisi oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | Creates a math array and places the specified element in it |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | Creates a math array and places specified elements in it |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```


Bir matematik dizisi oluşturur ve belirtilen öğeyi içine yerleştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | dizide yerleştirilecek matematik öğesi |

**Döndürür:**
[IMathArray](../../com.aspose.slides/imatharray) - yeni matematik dizisi
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```


Bir matematik dizisi oluşturur ve belirtilen öğeleri içine yerleştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | dizide yerleştirilecek matematik öğeleri |

**Döndürür:**
[IMathArray](../../com.aspose.slides/imatharray) - yeni matematik dizisi