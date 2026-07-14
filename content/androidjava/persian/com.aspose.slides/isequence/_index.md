---
title: ISequence
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر مجموعه دنباله‌ای از افکت‌ها.
type: docs
url: /fa/com.aspose.slides/isequence/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

نمایانگر دنباله (مجموعه‌ای از افکت‌ها).

## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد افکت‌ها در یک دنباله را بازمی‌گرداند. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | افکت مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک افکت را از یک مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام افکت‌ها را از یک مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | یک افکت را در ایندکس مشخص‌شده بازمی‌گرداند. |
| [getTriggerShape()](#getTriggerShape--) | هدف شکل را برای دنباله INTERACTIVE بازمی‌گرداند یا تنظیم می‌کند. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | هدف شکل را برای دنباله INTERACTIVE بازمی‌گرداند یا تنظیم می‌کند. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | افکت را برای شکل مشخص‌شده حذف می‌کند. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | آرایه‌ای از افکت‌ها برای شکل مشخص‌شده را بازمی‌گرداند. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | آرایه‌ای از افکت‌ها برای پاراگراف مشخص‌شده را بازمی‌گرداند. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | تعداد افکت‌ها برای شکل مشخص‌شده را بازمی‌گرداند. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | افکت جدید را به انتهای دنباله اضافه می‌کند. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | افکت انیمیشن جدید برای پاراگراف را به انتهای دنباله اضافه می‌کند. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | افکت انیمیشن جدید چارت برای دسته یا سری را به انتهای دنباله اضافه می‌کند. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | افکت انیمیشن جدید چارت برای عناصر در دسته یا سری را به انتهای دنباله اضافه می‌کند. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد افکت‌ها در یک دنباله را بازمی‌گرداند. فقط‌خواندنی int.

**باز می‌گرداند:**  
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

افکت مشخص‌شده را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | افکتی که باید حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

یک افکت را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس افکتی که باید حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام افکت‌ها را از یک مجموعه حذف می‌کند.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

یک افکت را در ایندکس مشخص‌شده بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصر. |

**باز می‌گرداند:**  
[IEffect](../../com.aspose.slides/ieffect) - شی [IEffect](../../com.aspose.slides/ieffect)

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

هدف شکل را برای دنباله INTERACTIVE بازمی‌گرداند یا تنظیم می‌کند. اگر دنباله تعاملی نباشد، null باز می‌گرداند. قابل خواندن/نوشتن [IShape](../../com.aspose.slides/ishape).

**باز می‌گرداند:**  
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

هدف شکل را برای دنباله INTERACTIVE بازمی‌گرداند یا تنظیم می‌کند. اگر دنباله تعاملی نباشد، null باز می‌گرداند. قابل خواندن/نوشتن [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

افکت را برای شکل مشخص‌شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شی شکل [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

آرایه‌ای از افکت‌ها برای شکل مشخص‌شده را بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شی شکل [IShape](../../com.aspose.slides/ishape) |

**باز می‌گرداند:**  
com.aspose.slides.IEffect[] - آرایه‌ای از افکت‌ها [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

آرایه‌ای از افکت‌ها برای پاراگراف مشخص‌شده را بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | شی پاراگراف [IParagraph](../../com.aspose.slides/iparagraph) |

**باز می‌گرداند:**  
com.aspose.slides.IEffect[] - آرایه‌ای از افکت‌ها [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

تعداد افکت‌ها برای شکل مشخص‌شده را بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شی شکل [IShape](../../com.aspose.slides/ishape) |

**باز می‌گرداند:**  
int - تعداد افکت‌ها

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

افکت جدید را به انتهای دنباله اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شی شکل [IShape](../../com.aspose.slides/ishape) برای اضافه کردن یک افکت |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌سازی افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**باز می‌گرداند:**  
[IEffect](../../com.aspose.slides/ieffect) - شی افکت جدید [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

افکت انیمیشن جدید برای پاراگراف را به انتهای دنباله اضافه می‌کند.

---

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // پاراگراف را برای افزودن افکت انتخاب کنید
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // افکت انیمیشن Fly را به پاراگراف انتخاب‌شده اضافه کنید
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | شی پاراگراف [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌سازی افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**باز می‌گرداند:**  
[IEffect](../../com.aspose.slides/ieffect) - شی افکت جدید [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

افکت انیمیشن جدید چارت برای دسته یا سری را به انتهای دنباله اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | شی چارت [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع افکت انیمیشن [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | اندیس |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌سازی افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**باز می‌گرداند:**  
[IEffect](../../com.aspose.slides/ieffect) - شی افکت جدید [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

افکت انیمیشن جدید چارت برای عناصر در دسته یا سری را به انتهای دنباله اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | شی چارت [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع افکت انیمیشن [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | اندیس سری چارت |
| categoriesIndex | int | اندیس دسته |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌سازی افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**باز می‌گرداند:**  
[IEffect](../../com.aspose.slides/ieffect) - شی افکت جدید [IEffect](../../com.aspose.slides/ieffect)