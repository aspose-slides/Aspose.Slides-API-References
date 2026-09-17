---
title: Audio class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/audio/
---
## Audio الفئة

يمثل ملف صوت مدمج.

يعرض نوع Audio الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`content_type`](/slides/python-net/ar/aspose.slides/audio/content_type/) | يرجع نوع MIME للصوت، مُشفر في [`Audio.binary_data`](/slides/python-net/ar/aspose.slides/audio/binary_data).<br/>            للقراءة فقط **str**. |
| [`binary_data`](/slides/python-net/ar/aspose.slides/audio/binary_data/) | يرجع نسخة من بيانات الصوت. في حال وجود كمية كبيرة من البيانات يُنصح <br/>            باستخدام طريقة [`Audio.get_stream`](/slides/python-net/ar/aspose.slides/audio/get_stream) لتجنب تحميل غير ضروري لبيانات الصوت<br/>            إلى الذاكرة أو حتى حدوث OutOfMemoryException.<br/>            للقراءة فقط **int**[]. |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ar/aspose.slides/audio/get_stream/#) | يرجع تدفق Stream للقراءة.<br/>            استخدم 'using' أو أغلق التدفق بعد الاستخدام. |


### انظر أيضاً
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)