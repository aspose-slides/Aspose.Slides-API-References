---
title: ISequence
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر مجموعه‌ای از افکت‌های توالی.
type: docs
url: /fa/com.aspose.slides/isequence/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

نمایانگر یک توالی (مجموعه‌ای از افکت‌ها).

## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد افکت‌ها در یک توالی را برمی‌گرداند. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | افکت مشخص‌شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک افکت را از مجموعه حذف می‌کند. |
| [clear()](#clear--) | همه افکت‌ها را از مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | یک افکت را در ایندکس مشخص برمی‌گرداند. |
| [getTriggerShape()](#getTriggerShape--) | هدف شکل را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | هدف شکل را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | افکت را برای شکل مشخص حذف می‌کند. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | آرایه‌ای از افکت‌ها را برای شکل مشخص برمی‌گرداند. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | آرایه‌ای از افکت‌ها را برای پاراگراف مشخص برمی‌گرداند. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | تعداد افکت‌ها را برای شکل مشخص برمی‌گرداند. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | افکت جدیدی را به انتهای توالی اضافه می‌کند. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | افکت انیمیشن جدیدی برای پاراگراف به انتهای توالی اضافه می‌کند. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | افکت انیمیشن جدید چارت را برای دسته یا سری به انتهای توالی اضافه می‌کند. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | افکت انیمیشن جدید چارت برای عناصر در دسته یا سری به انتهای توالی اضافه می‌کند. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد افکت‌ها در یک توالی را برمی‌گرداند. فقط-خواندنی int.

**بازگرداندن:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```


افکت مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | افکتی که باید حذف شود. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


یک افکت را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس افکتی که باید حذف شود. |
### clear() {#clear--}
```
public abstract void clear()
```


همه افکت‌ها را از مجموعه حذف می‌کند.
### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```


یک افکت را در ایندکس مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصر. |

**بازگرداندن:**
[IEffect](../../com.aspose.slides/ieffect) - شیء [IEffect](../../com.aspose.slides/ieffect)
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```


هدف شکل را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. اگر توالی تعاملی نباشد null برمی‌گرداند. خواندنی-نوشتنی [IShape](../../com.aspose.slides/ishape).

**بازگرداندن:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```


هدف شکل را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. اگر توالی تعاملی نباشد null برمی‌گرداند. خواندنی-نوشتنی [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```


افکت را برای شکل مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شیء شکل [IShape](../../com.aspose.slides/ishape) |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```


آرایه‌ای از افکت‌ها را برای شکل مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شیء شکل [IShape](../../com.aspose.slides/ishape) |

**بازگرداندن:**
com.aspose.slides.IEffect[] - آرایه‌ای از افکت‌ها [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```


آرایه‌ای از افکت‌ها را برای پاراگراف مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | شیء پاراگرای [IParagraph](../../com.aspose.slides/iparagraph) |

**بازگرداندن:**
com.aspose.slides.IEffect[] - آرایه‌ای از افکت‌ها [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```


تعداد افکت‌ها را برای شکل مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شیء شکل [IShape](../../com.aspose.slides/ishape) |

**بازگرداندن:**
int - تعداد افکت‌ها int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```


افکت جدیدی را به انتهای توالی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شیء شکل [IShape](../../com.aspose.slides/ishape) برای اضافه‌کردن افکت |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌سازی افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگرداندن:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```


افکت انیمیشن جدیدی برای پاراگراف به انتهای توالی اضافه می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // پاراگراف را برای افزودن افکت انتخاب کنید
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // افزودن افکت انیمیشن Fly به پاراگراف انتخاب شده
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | شیء پاراگراف [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌سازی افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگرداندن:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```


افکت انیمیشن جدید چارت را برای دسته یا سری به انتهای توالی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | شیء چارت [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع افکت انیمیشن [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | ایندکس |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌سازی افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگرداندن:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```


افکت انیمیشن جدید چارت برای عناصر در دسته یا سری به انتهای توالی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | شیء چارت [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع افکت انیمیشن [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | ایندکس سری چارت |
| categoriesIndex | int | ایندکس دسته |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌سازی افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگرداندن:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)