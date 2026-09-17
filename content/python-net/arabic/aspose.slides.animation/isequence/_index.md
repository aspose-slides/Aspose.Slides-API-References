---
title: ISequence class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.animation/isequence/
---
## ISequence فئة

يمثل تسلسلاً (مجموعة من التأثيرات).

يعرض نوع ISequence الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`count`](/slides/python-net/ar/aspose.slides.animation/isequence/count/) | يرْجع عدد التأثيرات في تسلسل.<br/>            قراءة فقط **int**. |
| [`trigger_shape`](/slides/python-net/ar/aspose.slides.animation/isequence/trigger_shape/) | يرْجع أو يعيّن هدف الشكل لتسلسل INTERACTIVE.<br/>            إذا لم يكن التسلسل تفاعليًا فسيعيد None.<br/>            قراءة/كتابة [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |

يرجع تأثيرًا عند الفهرس المحدد.

## المؤشر

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides.animation/isequence/__getitem__/) | فهرس |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/ar/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | إضافة تأثير جديد إلى نهاية التسلسل. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/ar/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | إضافة تأثير حركة جديد للفقرة إلى نهاية التسلسل. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/ar/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | يضيف تأثير حركة مخطط جديد للفئة أو السلسلة إلى نهاية التسلسل. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/ar/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | يضيف تأثير حركة مخطط جديد للعناصر في الفئة أو السلسلة إلى نهاية التسلسل. |
| [`remove(self, item)`](/slides/python-net/ar/aspose.slides.animation/isequence/remove/#ieffect) | يزيل التأثير المحدد من مجموعة. |
| [`remove_at(self, index)`](/slides/python-net/ar/aspose.slides.animation/isequence/remove_at/#int) | يزيل تأثيرًا من مجموعة. |
| [`clear(self)`](/slides/python-net/ar/aspose.slides.animation/isequence/clear/#) | يزيل جميع التأثيرات من مجموعة. |
| [`remove_by_shape(self, shape)`](/slides/python-net/ar/aspose.slides.animation/isequence/remove_by_shape/#ishape) | إزالة تأثير للشكل المحدد. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/ar/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | يرْجع مصفوفة من التأثيرات للشكل المحدد. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/ar/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | يرْجع مصفوفة من التأثيرات للفقرة المحددة. |
| [`get_count(self, shape)`](/slides/python-net/ar/aspose.slides.animation/isequence/get_count/#ishape) | يرْجع عدد التأثيرات للشكل المحدد. |


### انظر أيضًا
* الوحدة [`aspose.slides.animation`](/slides/python-net/ar/aspose.slides.animation)
* المكتبة [`Aspose.Slides`](/slides/python-net)