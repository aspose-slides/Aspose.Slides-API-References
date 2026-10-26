---
title: ISequence
second_title: Aspose.Slides لأجهزة Android عبر مرجع API Java
description: يمثل مجموعة تسلسل من التأثيرات.
type: docs
url: /ar/com.aspose.slides/isequence/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

يمثل تسلسلاً (مجموعة من التأثيرات).
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | تُعيد عدد التأثيرات في تسلسل. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | يزيل التأثير المحدد من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل تأثيرًا من مجموعة. |
| [clear()](#clear--) | يزيل جميع التأثيرات من مجموعة. |
| [get_Item(int index)](#get-Item-int-) | تُعيد تأثيرًا عند الفهرس المحدد. |
| [getTriggerShape()](#getTriggerShape--) | تُعيد أو تُعيّن هدف الشكل لتسلسل INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | تُعيد أو تُعيّن هدف الشكل لتسلسل INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | إزالة التأثير للشكل المحدد. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | تُعيد مصفوفة من التأثيرات للشكل المحدد. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | تُعيد مصفوفة من التأثيرات للفقرة المحددة. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | تُعيد عدد التأثيرات للشكل المحدد. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | إضافة تأثير جديد إلى نهاية التسلسل. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | إضافة تأثير تحريك جديد للفقرة إلى نهاية التسلسل. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | يضيف تأثير التحريك الجديد للمخطط للفئة أو السلسلة إلى نهاية التسلسل. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | يضيف تأثير التحريك الجديد للمخطط للعناصر في الفئة أو السلسلة إلى نهاية التسلسل. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

تُعيد عدد التأثيرات في تسلسل. قراءة-فقط int.

**الإرجاع:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

يزيل التأثير المحدد من مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | التأثير لإزالته. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل تأثيرًا من مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس التأثير لإزالته int |
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع التأثيرات من مجموعة.
### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

تُعيد تأثيرًا عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - الكائن [IEffect](../../com.aspose.slides/ieffect).
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

تُعيد أو تُعيّن هدف الشكل لتسلسل INTERACTIVE. إذا كان التسلسل غير تفاعلي فإنها تُعيد null. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

تُعيد أو تُعيّن هدف الشكل لتسلسل INTERACTIVE. إذا كان التسلسل غير تفاعلي فإنها تُعيد null. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

إزالة التأثير للشكل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

تُعيد مصفوفة من التأثيرات للشكل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) |

**الإرجاع:**
com.aspose.slides.IEffect[] - مصفوفة من التأثيرات [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

تُعيد مصفوفة من التأثيرات للفقرة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | كائن الفقرة [IParagraph](../../com.aspose.slides/iparagraph) |

**الإرجاع:**
com.aspose.slides.IEffect[] - مصفوفة من التأثيرات [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

تُعيد عدد التأثيرات للشكل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) |

**الإرجاع:**
int - عدد التأثيرات int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

إضافة تأثير جديد إلى نهاية التسلسل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) لإضافة تأثير |
| effectType | int | نوع تأثير التحريك [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنواع فرعية لتأثير التحريك [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع تشغيل التأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

إضافة تأثير تحريك جديد للفقرة إلى نهاية التسلسل.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // حدد الفقرة لإضافة تأثير
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // أضف تأثير التحريك Fly إلى الفقرة المحددة
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | كائن الفقرة [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | نوع تأثير التحريك [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | الأنواع الفرعية لتأثير التحريك [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع تشغيل التأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

يضيف تأثير التحريك الجديد للمخطط للفئة أو السلسلة إلى نهاية التسلسل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | كائن المخطط [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع تأثير التحريك [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | الفهرس int |
| effectType | int | نوع تأثير التحريك [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | الأنواع الفرعية لتأثير التحريك [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع تشغيل التأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

يضيف تأثير التحريك الجديد للمخطط للعناصر في الفئة أو السلسلة إلى نهاية التسلسل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | كائن المخطط [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع تأثير التحريك [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | فهرس سلسلة المخطط int |
| categoriesIndex | int | فهرس الفئة int |
| effectType | int | نوع تأثير التحريك [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | الأنواع الفرعية لتأثير التحريك [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع تشغيل التأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)