---
title: Portion class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/portion/
---
## Portion فئة

Represents a portion of text inside a text paragraph.

The Portion type exposes the following members:

## المُنشئات

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides/portion/__init__/#) | ينشئ نسخة جديدة من Portion فئة. |
| [`__init__(self, str)`](/slides/python-net/ar/aspose.slides/portion/__init__/#str) | ينشئ نسخة جديدة من Portion فئة. |
| [`__init__(self, portion)`](/slides/python-net/ar/aspose.slides/portion/__init__/#portion) | ينشئ نسخة جديدة من Portion فئة. |

## الخصائص

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/ar/aspose.slides/portion/portion_format/) | يعيد كائن التنسيق الذي يحتوي على خصائص التنسيق المحددة صراحةً للجزء النصي دون تطبيق الوراثة.<br/>            قراءة فقط [`IPortionFormat`](/slides/python-net/ar/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ar/aspose.slides/portion/text/) | يحصل أو يضبط النص العادي للجزء.<br/>            قراءة/كتابة **str**. |
| [`field`](/slides/python-net/ar/aspose.slides/portion/field/) | يعيد حقلًا من هذا الجزء.<br/>            قراءة فقط [`IField`](/slides/python-net/ar/aspose.slides/ifield). |
| [`slide`](/slides/python-net/ar/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/portion/presentation/) |  |

## الطرق

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ar/aspose.slides/portion/add_field/#ifieldtype) | يحول هذا الجزء إلى حقل يتم تحديثه تلقائيًا. |
| [`add_field(self, internal_string)`](/slides/python-net/ar/aspose.slides/portion/add_field/#str) | يحول هذا الجزء إلى حقل يتم تحديثه تلقائيًا. |
| [`remove_field(self)`](/slides/python-net/ar/aspose.slides/portion/remove_field/#) | يحول هذا الجزء الحقل إلى الجزء البسيط. |
| [`get_rect(self)`](/slides/python-net/ar/aspose.slides/portion/get_rect/#) | احصل على إحداثيات المستطيل الذي يحد الجزء. المستطيل يشمل جميع سطر<br/>             النص في الجزء، بما في ذلك السطور الفارغة. |
| [`get_coordinates(self)`](/slides/python-net/ar/aspose.slides/portion/get_coordinates/#) | احصل على إحداثيات بداية الجزء. إحداثي X للنقطة يمثل بداية الجزء من الحرف الأول بما في ذلك المسافة الجانبية اليسرى. إحداثي Y يشمل المسافة العلوية. |

### انظر أيضا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)