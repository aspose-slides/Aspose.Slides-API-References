---
title: ITextAnimationCollection
second_title: Aspose.Slides Java API Referansı
description: Metin animasyonlarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/itextanimationcollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Metin animasyonlarının koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Dizine göre öğeyi döndürür. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Tüm öğeleri döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```

Dizine göre öğeyi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
``` 
public abstract ITextAnimation[] get_Item(IShape shape)
```

Tüm öğeleri döndürür

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) öğe. |

**Döndürür:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) dizisi