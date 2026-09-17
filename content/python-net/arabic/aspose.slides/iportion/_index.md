---
title: IPortion class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/iportion/
---
## IPortion فئة

يمثل جزءًا من النص داخل فقرة نصية.

نوع IPortion يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`portion_format`](/slides/python-net/ar/aspose.slides/iportion/portion_format/) | يرجع كائن التنسيق الذي يحتوي على خصائص التنسيق المحددة صراحةً للجزء النصي دون تطبيق الوراثة.<br/>            قراءة فقط [`IPortionFormat`](/slides/python-net/ar/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ar/aspose.slides/iportion/text/) | يحصل أو يضبط النص العادي للجزء.<br/>            قراءة/كتابة **str**. |
| [`field`](/slides/python-net/ar/aspose.slides/iportion/field/) | يرجع حقلًا لهذا الجزء.<br/>            قراءة فقط [`IField`](/slides/python-net/ar/aspose.slides/ifield). |
| [`slide`](/slides/python-net/ar/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/iportion/presentation/) |  |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ar/aspose.slides/iportion/add_field/#ifieldtype) | يقوم بتحويل هذا الجزء إلى حقل محدث تلقائيًا. |
| [`add_field(self, internal_string)`](/slides/python-net/ar/aspose.slides/iportion/add_field/#str) | يقوم بتحويل هذا الجزء إلى حقل محدث تلقائيًا. |
| [`remove_field(self)`](/slides/python-net/ar/aspose.slides/iportion/remove_field/#) | يقوم بتحويل هذا الجزء الحقل إلى الجزء البسيط. |
| [`get_rect(self)`](/slides/python-net/ar/aspose.slides/iportion/get_rect/#) | احصل على إحداثيات المستطيل الذي يحد الجزء. يشمل المستطيل جميع سطور النص في الجزء، بما في ذلك السطور الفارغة. |
| [`get_coordinates(self)`](/slides/python-net/ar/aspose.slides/iportion/get_coordinates/#) | احصل على إحداثيات بداية الجزء. إحداثية X للنقطة تمثل بداية الجزء من الحرف الأول بما في ذلك البعد اليساري. إحداثية Y تشمل البعد العلوي. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)