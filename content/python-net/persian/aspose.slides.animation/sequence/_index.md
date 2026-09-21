---
title: Sequence class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.animation/sequence/
---
## Sequence کلاس

دنباله (مجموعه‌ای از افکت‌ها) را نمایندگی می‌کند.

نوع Sequence اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`count`](/slides/python-net/fa/aspose.slides.animation/sequence/count/) | تعداد افکت‌ها در یک توالی را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`trigger_shape`](/slides/python-net/fa/aspose.slides.animation/sequence/trigger_shape/) | مقدار هدف شکل را برای توالی INTERACTIVE برمی‌گرداند یا تنظیم می‌کند.<br/>            اگر توالی تعاملی نباشد، None برمی‌گرداند.<br/>            خواندن/نوشتن [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |

یک افکت را در شاخص مشخص شده برمی‌گرداند.

## اندیس‌گذار

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides.animation/sequence/__getitem__/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/fa/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | افکت جدیدی را به انتهای توالی اضافه می‌کند. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/fa/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | افکت انیمیشن جدیدی برای پاراگراف به انتهای توالی اضافه می‌کند. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/fa/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | افکت انیمیشن جدید نمودار برای دسته یا سری را به انتهای توالی اضافه می‌کند. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/fa/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | افکت انیمیشن جدید نمودار برای عناصر در دسته یا سری را به انتهای توالی اضافه می‌کند. |
| [`remove(self, item)`](/slides/python-net/fa/aspose.slides.animation/sequence/remove/#ieffect) | افکت مشخص شده را از مجموعه حذف می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides.animation/sequence/remove_at/#int) | یک افکت را از مجموعه حذف می‌کند. |
| [`clear(self)`](/slides/python-net/fa/aspose.slides.animation/sequence/clear/#) | تمام افکت‌های موجود در مجموعه را حذف می‌کند. |
| [`remove_by_shape(self, shape)`](/slides/python-net/fa/aspose.slides.animation/sequence/remove_by_shape/#ishape) | افکت مربوط به شکل مشخص شده را حذف می‌کند. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/fa/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | آرایه‌ای از افکت‌ها برای شکل مشخص شده برمی‌گرداند. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/fa/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | آرایه‌ای از افکت‌ها برای پاراگراف مشخص شده برمی‌گرداند. |
| [`get_count(self, shape)`](/slides/python-net/fa/aspose.slides.animation/sequence/get_count/#ishape) | تعداد افکت‌ها برای شکل مشخص شده را برمی‌گرداند. |


### موارد مرتبط
* ماژول [`aspose.slides.animation`](/slides/python-net/fa/aspose.slides.animation)
* کتابخانه [`Aspose.Slides`](/slides/python-net)