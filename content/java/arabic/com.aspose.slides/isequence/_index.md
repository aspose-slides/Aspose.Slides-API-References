---
title: ISequence
second_title: مرجع API لـ Aspose.Slides للجاڤا
description: يمثل مجموعة تسلسل من التأثيرات.
type: docs
url: /ar/com.aspose.slides/isequence/
---
**كل الواجهات المُنفّذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

يمثل تسلسل (مجموعة من التأثيرات).
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يعيد عدد التأثيرات في تسلسل. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | يزيل التأثير المحدد من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل تأثيرًا من مجموعة. |
| [clear()](#clear--) | يزيل جميع التأثيرات من مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد تأثيرًا عند الفهرس المحدد. |
| [getTriggerShape()](#getTriggerShape--) | يعيد أو يعيّن هدف الشكل لتسلسل INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | يعيد أو يعيّن هدف الشكل لتسلسل INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | يزيل التأثير للشكل المحدد. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | يعيد مصفوفة من التأثيرات للشكل المحدد. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | يعيد مصفوفة من التأثيرات للفقرة المحددة. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | يعيد عدد التأثيرات للشكل المحدد. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | يضيف تأثيرًا جديدًا إلى نهاية التسلسل. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | يضيف تأثيرًا جديدًا للرسوم المتحركة للفقرة إلى نهاية التسلسل. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | يضيف تأثير رسم بياني جديد للرسوم المتحركة للفئة أو السلسلة إلى نهاية التسلسل. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | يضيف تأثير رسم بياني جديد للرسوم المتحركة للعناصر في الفئة أو السلسلة إلى نهاية التسلسل. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

يعيد عدد التأثيرات في تسلسل. قراءة فقط int.

**الإرجاع:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

يزيل التأثير المحدد من مجموعة.

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | التأثير لإزالته. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل تأثيرًا من مجموعة.

**المعلمات:**
| المعامل | نوع | الوصف |
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

يعيد تأثيرًا عند الفهرس المحدد.

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - الكائن [IEffect](../../com.aspose.slides/ieffect).

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

يعيد أو يعيّن هدف الشكل لتسلسل INTERACTIVE. إذا لم يكن التسلسل تفاعليًا فيعيد null. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

يعيد أو يعيّن هدف الشكل لتسلسل INTERACTIVE. إذا لم يكن التسلسل تفاعليًا فيعيد null. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

يزيل التأثير للشكل المحدد.

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

يعيد مصفوفة من التأثيرات للشكل المحدد.

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) |

**الإرجاع:**
com.aspose.slides.IEffect[] - مصفوفة من التأثيرات [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

يعيد مصفوفة من التأثيرات للفقرة المحددة.

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | كائن الفقرة [IParagraph](../../com.aspose.slides/iparagraph) |

**الإرجاع:**
com.aspose.slides.IEffect[] - مصفوفة من التأثيرات [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

يعيد عدد التأثيرات للشكل المحدد.

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) |

**الإرجاع:**
int - عدد التأثيرات int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

أضف تأثيرًا جديدًا إلى نهاية التسلسل.

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) لإضافة تأثير. |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنوع فرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع المشغل للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

أضف تأثير رسوم متحركة جديد للفقرة إلى نهاية التسلسل.

---

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // اختر الفقرة لإضافة التأثير
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // أضف تأثير الطيران إلى الفقرة المحددة
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | كائن الفقرة [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنوع فرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع المشغل للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

يضيف تأثير رسوم متحركة جديد للمخطط للفئة أو السلسلة إلى نهاية التسلسل.

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | كائن المخطط [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع تأثير الرسوم المتحركة [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | فهرس int |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنوع فرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع المشغل للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

يضيف تأثير رسوم متحركة جديد للمخطط للعناصر في الفئة أو السلسلة إلى نهاية التسلسل.

**المعلمات:**
| المعامل | نوع | الوصف |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | كائن المخطط [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع تأثير الرسوم المتحركة [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | فهرس سلسلة المخطط int |
| categoriesIndex | int | فهرس الفئة int |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنوع فرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع المشغل للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)