---
title: Sequence
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش‌دهنده‌ی مجموعه توالی افکت‌ها.
type: docs
url: /fa/com.aspose.slides/sequence/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

نمایش‌دهنده‌ی توالی (مجموعه‌ای از افکت‌ها).

## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد افکت‌ها در یک sequense را برمی‌گرداند. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | افکت مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک افکت را از یک مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام افکت‌ها را از یک مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | یک افکت را در اندیس مشخص‌شده باز می‌گرداند. |
| [iterator()](#iterator--) | یک enumerator را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [getTriggerShape()](#getTriggerShape--) | هدف شکل را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | هدف شکل را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | افکت را برای شکل مشخص‌شده حذف می‌کند. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | آرایه‌ای از افکت‌ها را برای شکل مشخص‌شده برمی‌گرداند. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | آرایه‌ای از افکت‌ها را برای پاراگراف مشخص‌شده برمی‌گرداند. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | تعداد افکت‌ها را برای شکل مشخص‌شده برمی‌گرداند. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | افکت جدیدی را به انتهای توالی اضافه می‌کند. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | افکت انیمیشن جدیدی برای پاراگراف به انتهای توالی اضافه می‌کند. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | افکت انیمیشن جدید نمودار را برای دسته یا سری به انتهای توالی اضافه می‌کند. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | افکت انیمیشن جدید نمودار را برای عناصر در دسته یا سری به انتهای توالی اضافه می‌کند. |

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد افکت‌ها در یک sequense را برمی‌گرداند. فقط‌خواندنی int.

**باز می‌گرداند:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

افکت مشخص‌شده را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | افکتی که باید حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

یک افکت را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس افکتی که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام افکت‌ها را از یک مجموعه حذف می‌کند.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

یک افکت را در اندیس مشخص‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصر. |

**باز می‌گرداند:**
[IEffect](../../com.aspose.slides/ieffect) - شیء [IEffect](../../com.aspose.slides/ieffect).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

یک enumerator را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - یک IGenericEnumerator که می‌توان برای پیمایش مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - یک java.util.Iterator برای کل مجموعه.

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

هدف شکل را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. اگر توالی interactive نباشد مقدار null برمی‌گردد. خواندنی/قابل نوشتن [IShape](../../com.aspose.slides/ishape).

**باز می‌گرداند:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

هدف شکل را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. اگر توالی interactive نباشد مقدار null برمی‌گردد. خواندنی/قابل نوشتن [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

افکت را برای شکل مشخص‌شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

آرایه‌ای از افکت‌ها را برای شکل مشخص‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**باز می‌گرداند:**
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

آرایه‌ای از افکت‌ها را برای پاراگراف مشخص‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**باز می‌گرداند:**
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

تعداد افکت‌ها را برای شکل مشخص‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**باز می‌گرداند:**
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

افکت جدیدی را به انتهای توالی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شیء Shape [IShape](../../com.aspose.slides/ishape) برای افزودن افکت |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌ساز افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**باز می‌گرداند:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

افکت انیمیشن جدیدی برای پاراگراف به انتهای توالی اضافه می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // پاراگراف را برای افزودن افکت انتخاب کنید
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // افزودن افکت انیمیشن Fly به پاراگراف انتخاب‌شده
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | شیء Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌ساز افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**باز می‌گرداند:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

افکت انیمیشن جدید نمودار را برای دسته یا سری به انتهای توالی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | شیء Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع افکت انیمیشن [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | اندیس int |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌ساز افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**باز می‌گرداند:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

افکت انیمیشن جدید نمودار را برای عناصر در دسته یا سری به انتهای توالی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | شیء Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع افکت انیمیشن [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | اندیس سری نمودار int |
| categoriesIndex | int | اندیس دسته int |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌ساز افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**باز می‌گرداند:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)