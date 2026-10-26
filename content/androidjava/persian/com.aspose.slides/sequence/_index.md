---
title: Sequence
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایشگر مجموعه‌ای از اثرهای توالی.
type: docs
url: /fa/com.aspose.slides/sequence/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Represents sequence (collection of effects).
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد اثرها در یک توالی را برمی‌گرداند. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | اثر مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک اثر را از یک مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام اثرها را از یک مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | یک اثر را در ایندکس مشخص‌شده برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که از مجموعه عبور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [getTriggerShape()](#getTriggerShape--) | هدف shape را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | هدف shape را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | حذف اثر برای shape مشخص‌شده. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | آرایه‌ای از اثرها برای shape مشخص‌شده را برمی‌گرداند. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | آرایه‌ای از اثرها برای پاراگراف مشخص‌شده را برمی‌گرداند. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | تعداد اثرها برای shape مشخص‌شده را برمی‌گرداند. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | افکت جدیدی را به انتهای توالی اضافه می‌کند. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | افکت انیمیشن جدید برای پاراگراف را به انتهای توالی اضافه می‌کند. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | افکت انیمیشن جدید نمودار برای دسته یا سری را به انتهای توالی اضافه می‌کند. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | افکت انیمیشن جدید نمودار برای عناصر در دسته یا سری را به انتهای توالی اضافه می‌کند. |
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد اثرها در یک توالی را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

اثر مشخص‌شده را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effect to remove. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

یک اثر را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | Index of a effect that should be deleted. |

### clear() {#clear--}
```
public final void clear()
```

تمام اثرها را از یک مجموعه حذف می‌کند.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

یک اثر را در ایندکس مشخص‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | Index of element. |

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect) - The [IEffect](../../com.aspose.slides/ieffect) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

یک enumerator که از مجموعه عبور می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - An java.util.Iterator for the entire collection.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

هدف shape را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. اگر توالی تعاملی نباشد، null برمی‌گرداند. خواندن/نوشتن [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

هدف shape را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند. اگر توالی تعاملی نباشد، null برمی‌گرداند. خواندن/نوشتن [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

حذف اثر برای shape مشخص‌شده.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

آرایه‌ای از اثرها برای shape مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**بازگشت:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

آرایه‌ای از اثرها برای پاراگراف مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**بازگشت:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

تعداد اثرها برای shape مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**بازگشت:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

افکت جدیدی را به انتهای توالی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) for adding an effect |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

افکت انیمیشن جدید برای پاراگراف را به انتهای توالی اضافه می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // پاراگرافی را که می‌خواهید اثر به آن اضافه کنید انتخاب کنید
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // افکت انیمیشن Fly را به پاراگراف انتخاب شده اضافه کنید
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph object [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

افکت انیمیشن جدید نمودار برای دسته یا سری را به انتهای توالی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart object [IChart](../../com.aspose.slides/ichart) |
| type | int | Type of an animation effect [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

افکت انیمیشن جدید نمودار برای عناصر در دسته یا سری را به انتهای توالی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart object [IChart](../../com.aspose.slides/ichart) |
| type | int | Type of an animation effect [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index of chart series int |
| categoriesIndex | int | Index of category int |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)