---
title: ITextAnimationCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایندهٔ مجموعه‌ای از انیمیشن‌های متن.
type: docs
url: /fa/com.aspose.slides/itextanimationcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

نمایش‌دهندهٔ مجموعه‌ای از انیمیشن‌های متن.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را بر اساس ایندکس برمی‌گرداند. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | تمام عناصر را برمی‌گرداند |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```

عنصری را بر اساس ایندکس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```

تمام عناصر را برمی‌گرداند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) عنصر. |

**بازگشت:**
com.aspose.slides.ITextAnimation[] - آرایه‌ای از [ITextAnimation](../../com.aspose.slides/itextanimation)