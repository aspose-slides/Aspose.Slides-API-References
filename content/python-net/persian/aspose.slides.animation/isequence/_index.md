---
title: ISequence class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.animation/isequence/
---
## ISequence کلاس

دنباله (مجموعه‌ای از افکت‌ها) را نشان می‌دهد.

نوع ISequence اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`count`](/slides/python-net/fa/aspose.slides.animation/isequence/count/) | تعداد افکت‌ها در یک دنباله را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`trigger_shape`](/slides/python-net/fa/aspose.slides.animation/isequence/trigger_shape/) | هدف شکل را برای دنباله INTERACTIVE برمی‌گرداند یا تنظیم می‌کند.<br/>            اگر دنباله تعاملی نباشد، None را برمی‌گرداند.<br/>            قابل‌خواندن/قابل‌نوشتن [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |

افکت را در اندیس مشخص شده برمی‌گرداند.

## شاخص

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides.animation/isequence/__getitem__/) | شاخص |

## متدها

| متد | توضیح |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/fa/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | افکت جدیدی را به انتهای دنباله اضافه می‌کند. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/fa/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | افکت انیمیشن جدیدی برای پاراگراف را به انتهای دنباله اضافه می‌کند. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/fa/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | افکت انیمیشن جدید نمودار برای دسته یا سری را به انتهای دنباله اضافه می‌کند. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/fa/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | افکت انیمیشن جدید نمودار برای عناصر در دسته یا سری را به انتهای دنباله اضافه می‌کند. |
| [`remove(self, item)`](/slides/python-net/fa/aspose.slides.animation/isequence/remove/#ieffect) | افکت مشخص شده را از یک مجموعه حذف می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides.animation/isequence/remove_at/#int) | یک افکت را از یک مجموعه حذف می‌کند. |
| [`clear(self)`](/slides/python-net/fa/aspose.slides.animation/isequence/clear/#) | تمام افکت‌ها را از یک مجموعه حذف می‌کند. |
| [`remove_by_shape(self, shape)`](/slides/python-net/fa/aspose.slides.animation/isequence/remove_by_shape/#ishape) | افکت مربوط به شکل مشخص شده را حذف می‌کند. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/fa/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | آرایه‌ای از افکت‌ها برای شکل مشخص شده را برمی‌گرداند. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/fa/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | آرایه‌ای از افکت‌ها برای پاراگراف مشخص شده را برمی‌گرداند. |
| [`get_count(self, shape)`](/slides/python-net/fa/aspose.slides.animation/isequence/get_count/#ishape) | تعداد افکت‌ها برای شکل مشخص شده را برمی‌گرداند. |

### موارد مرتبط
* ماژول [`aspose.slides.animation`](/slides/python-net/fa/aspose.slides.animation)
* کتابخانه [`Aspose.Slides`](/slides/python-net)