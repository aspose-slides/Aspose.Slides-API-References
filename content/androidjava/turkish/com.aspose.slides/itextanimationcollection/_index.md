---
title: ITextAnimationCollection
second_title: Java API Referansı ile Android için Aspose.Slides
description: Metin animasyonlarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/itextanimationcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Metin animasyonlarının koleksiyonunu temsil eder.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndekse göre öğeyi döndürür. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Tüm öğeleri döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


İndekse göre öğeyi döndürür.

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