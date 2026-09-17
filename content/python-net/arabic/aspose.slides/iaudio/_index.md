---
title: IAudio class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/iaudio/
---
## IAudio فئة

يمثل ملف صوت مضمن.

تعرض نوع IAudio الأعضاء التالية:

## خصائص

| الخاصية | الوصف |
| :- | :- |
| [`content_type`](/slides/python-net/ar/aspose.slides/iaudio/content_type/) | يرجع نوع MIME لصوت، مُشفَّر في [`IAudio.binary_data`](/slides/python-net/ar/aspose.slides/iaudio/binary_data).<br/>            للقراءة فقط **str**. |
| [`binary_data`](/slides/python-net/ar/aspose.slides/iaudio/binary_data/) | يرجع نسخة من بيانات الصوت. في حالة كمية كبيرة من البيانات، يُنصح <br/>            باستخدام طريقة [`IAudio.get_stream`](/slides/python-net/ar/aspose.slides/iaudio/get_stream) لمنع تحميل بيانات الصوت غير الضروري<br/>            إلى الذاكرة أو حتى استثناء OutOfMemoryException.<br/>            للقراءة فقط **int**[]. |

## طرق

| الطريقة | الوصف |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ar/aspose.slides/iaudio/get_stream/#) | يرجع تدفق Stream للقراءة.<br/>            استخدم 'using' أو أغلق التدفق بعد الاستخدام. |

### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)