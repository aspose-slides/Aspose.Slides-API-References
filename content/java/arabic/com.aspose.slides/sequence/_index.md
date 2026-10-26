---
title: Sequence
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة Java
description: يمثل مجموعة تسلسل من التأثيرات.
type: docs
url: /ar/com.aspose.slides/sequence/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)  
```
public final class Sequence implements ISequence
```

يمثل تسلسلاً (مجموعة من التأثيرات).

## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | يعيد عدد التأثيرات في تسلسل. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | يزيل التأثير المحدد من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل تأثيرًا من مجموعة. |
| [clear()](#clear--) | يزيل جميع التأثيرات من مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد تأثيرًا عند الفهرس المحدد. |
| [iterator()](#iterator--) | يعيد مكرّرًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر Java للمجموعة بأكملها. |
| [getTriggerShape()](#getTriggerShape--) | يعيد أو يضبط هدف الشكل لتسلسل INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | يعيد أو يضبط هدف الشكل لتسلسل INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | إزالة التأثير للشكل المحدد. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | يعيد مصفوفة من التأثيرات للشكل المحدد. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | يعيد مصفوفة من التأثيرات للفقرة المحددة. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | يعيد عدد التأثيرات للشكل المحدد. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | إضافة تأثير جديد إلى نهاية التسلسل. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | إضافة تأثير حركة جديد للفقرة إلى نهاية التسلسل. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | يضيف تأثير حركة المخطط الجديد للفئة أو السلسلة إلى نهاية التسلسل. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | يضيف تأثير حركة المخطط الجديد للعناصر في الفئة أو السلسلة إلى نهاية التسلسل. |

### getCount() {#getCount--}
```
public final int getCount()
```

يعيد عدد التأثيرات في تسلسل. قراءة فقط int.

**الإرجاع:**  
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

يزيل التأثير المحدد من مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | التأثير لإزالته. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل تأثيرًا من مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
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

يعيد تأثيرًا عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**  
[IEffect](../../com.aspose.slides/ieffect) - The [IEffect](../../com.aspose.slides/ieffect) object.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

يعيد مكرّرًا يتنقل عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

يعيد مكرّر Java للمجموعة بأكملها.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - java.util.Iterator للمجموعة بأكملها.

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

يعيد أو يضبط هدف الشكل لتسلسل INTERACTIVE. إذا لم يكن التسلسل تفاعليًا فإنه يعيد null. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

يعيد أو يضبط هدف الشكل لتسلسل INTERACTIVE. إذا لم يكن التسلسل تفاعليًا فإنه يعيد null. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

إزالة التأثير للشكل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

يعيد مصفوفة من التأثيرات للشكل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**الإرجاع:**  
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

يعيد مصفوفة من التأثيرات للفقرة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**الإرجاع:**  
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

يعيد عدد التأثيرات للشكل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**الإرجاع:**  
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

إضافة تأثير جديد إلى نهاية التسلسل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) لإضافة تأثير |
| effectType | int | نوع تأثير الحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنواع فرعية لتأثير الحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع الزناد للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**  
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

إضافة تأثير حركة جديد للفقرة إلى نهاية التسلسل.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // اختر الفقرة لإضافة تأثير
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // إضافة تأثير الحركة Fly إلى الفقرة المختارة
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | كائن الفقرة [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | نوع تأثير الحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنواع فرعية لتأثير الحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع الزناد للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**  
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

يضيف تأثير حركة المخطط الجديد للفئة أو السلسلة إلى نهاية التسلسل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | كائن المخطط [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع تأثير الحركة [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | فهرس int |
| effectType | int | نوع تأثير الحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنواع فرعية لتأثير الحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع الزناد للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**  
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

يضيف تأثير حركة المخطط الجديد للعناصر في الفئة أو السلسلة إلى نهاية التسلسل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | كائن المخطط [IChart](../../com.aspose.slides/ichart) |
| type | int | نوع تأثير الحركة [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | فهرس سلسلة المخطط int |
| categoriesIndex | int | فهرس الفئة int |
| effectType | int | نوع تأثير الحركة [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | أنواع فرعية لتأثير الحركة [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع الزناد للتأثير [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**الإرجاع:**  
[IEffect](../../com.aspose.slides/ieffect) - كائن تأثير جديد [IEffect](../../com.aspose.slides/ieffect)