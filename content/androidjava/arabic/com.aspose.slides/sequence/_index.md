---
title: Sequence
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة تسلسلية من التأثيرات.
type: docs
url: /ar/com.aspose.slides/sequence/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

يمثل تسلسلاً (مجموعة من التأثيرات).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يرجع عدد التأثيرات في تسلسل. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | يزيل التأثير المحدد من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل تأثيرًا من مجموعة. |
| [clear()](#clear--) | يزيل جميع التأثيرات من مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يرجع تأثيرًا في الفهرس المحدد. |
| [iterator()](#iterator--) | يرجع كائن تعداد يتجول خلال المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مُتكرر java للمجموعة بأكملها. |
| [getTriggerShape()](#getTriggerShape--) | يرجع أو يضبط هدف الشكل لتسلسل INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | يرجع أو يضبط هدف الشكل لتسلسل INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | إزالة التأثير للشكل المحدد. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | يرجع مصفوفة من التأثيرات للشكل المحدد. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | يرجع مصفوفة من التأثيرات للفقرة المحددة. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | يرجع عدد التأثيرات للشكل المحدد. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | أضف تأثيرًا جديدًا إلى نهاية التسلسل. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | أضف تأثيرًا حركيًا جديدًا للفقرة إلى نهاية التسلسل. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | يضيف تأثير الرسوم البيانية المتحرك الجديد للفئة أو السلسلة إلى نهاية التسلسل. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | يضيف تأثير الرسوم البيانية المتحرك الجديد للعناصر في الفئة أو السلسلة إلى نهاية التسلسل. |

### getCount() {#getCount--}
```
public final int getCount()
```

يرجع عدد التأثيرات في تسلسل. قراءة فقط int.

**الإرجاع:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

يزيل التأثير المحدد من مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | التأثير المراد إزالته. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل تأثيرًا من مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس التأثير الذي يجب حذفه. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع التأثيرات من مجموعة.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

يرجع تأثيرًا في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - The [IEffect](../../com.aspose.slides/ieffect) object.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

يرجع كائن تعداد يتجول خلال المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - مُعداد IGenericEnumerator يمكن استخدامه للتجول عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

يرجع java iterator للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - java.util.Iterator للمجموعة بأكملها.

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

يرجع أو يضبط هدف الشكل لتسلسل INTERACTIVE. إذا لم يكن التسلسل تفاعليًا فإنه يرجع null. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

يرجع أو يضبط هدف الشكل لتسلسل INTERACTIVE. إذا لم يكن التسلسل تفاعليًا فإنه يرجع null. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

إزالة التأثير للشكل المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

يرجع مصفوفة من التأثيرات للشكل المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**الإرجاع:**
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

يرجع مصفوفة من التأثيرات للفقرة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**الإرجاع:**
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

يرجع عدد التأثيرات للشكل المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**الإرجاع:**
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

أضف تأثيرًا جديدًا إلى نهاية التسلسل.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) لإضافة تأثير. |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | الأنواع الفرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع الزناد للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

أضف تأثيرًا حركيًا جديدًا للفقرة إلى نهاية التسلسل.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // حدد الفقرة لإضافة تأثير
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // أضف تأثير الحركة Fly للفقرة المحددة
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | كائن الفقرة [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | الأنواع الفرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع الزناد للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

يضيف تأثير الرسوم البيانية المتحرك الجديد للفئة أو السلسلة إلى نهاية التسلسل.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | كائن الرسم البياني [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع تأثير الرسوم المتحركة [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | فهرس int |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | الأنواع الفرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع الزناد للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

يضيف تأثير الرسوم البيانية المتحرك الجديد للعناصر في الفئة أو السلسلة إلى نهاية التسلسل.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | كائن الرسم البياني [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع تأثير الرسوم المتحركة [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | فهرس سلسلة الرسم البياني int |
| categoriesIndex | int | فهرس الفئة int |
| effectType | int | نوع تأثير الرسوم المتحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | الأنواع الفرعية لتأثير الرسوم المتحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع الزناد للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)