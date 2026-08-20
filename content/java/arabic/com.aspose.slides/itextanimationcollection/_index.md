---
title: ITextAnimationCollection
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: يمثل مجموعة من الرسوم المتحركة النصية.
type: docs
url: /ar/com.aspose.slides/itextanimationcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

يمثل مجموعة من الرسوم المتحركة النصية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع العنصر بواسطة الفهرس. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | يرجع جميع العناصر |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```

يرجع العنصر بواسطة الفهرس.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```

يرجع جميع العناصر

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) عنصر. |

**الإرجاع:**
com.aspose.slides.ITextAnimation[] - مصفوفة من [ITextAnimation](../../com.aspose.slides/itextanimation)