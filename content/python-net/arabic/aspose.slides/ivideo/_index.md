---
title: IVideo class
second_title: مرجع API لـ Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ivideo/
---
## IVideo فئة

يمثل فيديو مدمجًا في عرض تقديمي.

نوع IVideo يُظهر الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`content_type`](/slides/python-net/ar/aspose.slides/ivideo/content_type/) | يرجع نوع MIME للفيديو، مُشفّر بـ [`IVideo.binary_data`](/slides/python-net/ar/aspose.slides/ivideo/binary_data).<br/>            قراءة فقط **str**. |
| [`binary_data`](/slides/python-net/ar/aspose.slides/ivideo/binary_data/) | يرجع نسخة من بيانات الصوت. في حالة كمية كبيرة من البيانات يُنصح باستخدام <br/>            طريقة [`IVideo.get_stream`](/slides/python-net/ar/aspose.slides/ivideo/get_stream) لمنع تحميل بيانات الفيديو غير الضروري إلى الذاكرة <br/>            أو حتى حدوث OutOfMemoryException.<br/>            قراءة فقط **int**[]. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ar/aspose.slides/ivideo/get_stream/#) | يرجع تدفق Stream للقراءة.<br/>            استخدم 'using' أو أغلق التدفق بعد الاستخدام. |


### انظر أيضاً
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)