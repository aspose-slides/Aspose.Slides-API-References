---
title: Sequence class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.animation/sequence/
---
## فئة Sequence

يمثل تسلسل (مجموعة من التأثيرات).

يعرض نوع Sequence الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`count`](/slides/python-net/ar/aspose.slides.animation/sequence/count/) | يعيد عدد التأثيرات في تسلسل.<br/>            قراءة فقط **int**. |
| [`trigger_shape`](/slides/python-net/ar/aspose.slides.animation/sequence/trigger_shape/) | يعيد أو يحدد هدف الشكل لتسلسل INTERACTIVE.<br/>            إذا لم يكن التسلسل تفاعليًا فإنها تعيد None.<br/>            قراءة/كتابة [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |

يعيد تأثيرًا في الفهرس المحدد.

## الفهرس

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides.animation/sequence/__getitem__/) |  |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/ar/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | أضف تأثيرًا جديدًا إلى نهاية التسلسل. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/ar/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | أضف تأثير رسوم متحركة جديد للفقرة إلى نهاية التسلسل. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/ar/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | يضيف تأثير رسوم متحركة جديد للمخطط للفئة أو السلسلة إلى نهاية التسلسل. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/ar/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | يضيف تأثير رسوم متحركة جديد للمخطط لعناصر في الفئة أو السلسلة إلى نهاية التسلسل. |
| [`remove(self, item)`](/slides/python-net/ar/aspose.slides.animation/sequence/remove/#ieffect) | يزيل التأثير المحدد من مجموعة. |
| [`remove_at(self, index)`](/slides/python-net/ar/aspose.slides.animation/sequence/remove_at/#int) | يزيل تأثيرًا من مجموعة. |
| [`clear(self)`](/slides/python-net/ar/aspose.slides.animation/sequence/clear/#) | يزيل جميع التأثيرات من مجموعة. |
| [`remove_by_shape(self, shape)`](/slides/python-net/ar/aspose.slides.animation/sequence/remove_by_shape/#ishape) | يزيل تأثيرًا للشكل المحدد. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/ar/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | يعيد مصفوفة من التأثيرات للشكل المحدد. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/ar/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | يعيد مصفوفة من التأثيرات للفقرة المحددة. |
| [`get_count(self, shape)`](/slides/python-net/ar/aspose.slides.animation/sequence/get_count/#ishape) | يعيد عدد التأثيرات للشكل المحدد. |

### انظر أيضًا
* الوحدة [`aspose.slides.animation`](/slides/python-net/ar/aspose.slides.animation)
* المكتبة [`Aspose.Slides`](/slides/python-net)