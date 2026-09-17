---
title: HtmlExternalResolver class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.importing/htmlexternalresolver/
---
## فئة HtmlExternalResolver

كائن رد الاتصال المستخدم من قبل روتين استيراد HTML للحصول على الكائنات المذكورة مثل الصور.
يمكن أن يؤدي استخدام هذا المحلل إلى حدوث ثغرة عندما يقوم ملف HTML مقدم من العميل بجعل برنامج الخادم يحصل على ملف محلي أو على شبكة. استخدمه بحذر. يوصى بعدم تحديد HtmlExternalResolver على الإطلاق (سيتم قراءة الكائنات المضمنة فقط) أو بإنشاء فئة فرعية تتحقق مما إذا كان الـ uri المحدد صالحًا.

يعرض نوع HtmlExternalResolver الأعضاء التالية:

## المنشئات

| منشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/ar/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | يقوم بحل الـ URI المطلق من الـ URI الأساسي والـ URIs النسبية. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/ar/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | يربط URI بكائن يحتوي على المورد الفعلي. |

### انظر أيضًا
* الوحدة [`aspose.slides.importing`](/slides/python-net/ar/aspose.slides.importing)
* المكتبة [`Aspose.Slides`](/slides/python-net)