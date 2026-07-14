---
title: ITextAnimationCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الرسوم المتحركة للنص.
type: docs
url: /ar/com.aspose.slides/itextanimationcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

يمثل مجموعة من الرسوم المتحركة للنص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد العنصر حسب الفهرس. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | يعيد جميع العناصر |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


يعيد العنصر حسب الفهرس.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


يعيد جميع العناصر

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) عنصر. |

**القيمة المرجعة:**
com.aspose.slides.ITextAnimation[] - مصفوفة من [ITextAnimation](../../com.aspose.slides/itextanimation)