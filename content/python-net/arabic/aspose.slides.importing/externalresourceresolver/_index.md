---
title: ExternalResourceResolver class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver فئة

فئة رد الاتصال المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات Html و Svg.  
استخدام هذا المحلّل قد يخلق ثغرة عندما يتم توفير ملف HTML أو SVG من قبل العميل مما يجعل برنامج الخادم يحصل على ملف محلي أو على شبكة. استخدمه بحذر. يُنصح بعدم تحديد ExternalResourceResolver على الإطلاق (سيتم قراءة الكائنات المدمجة فقط) أو إنشاء فئة فرعية تتحقق مما إذا كان uri المحدد صالحًا.

نوع ExternalResourceResolver يعرض الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/ar/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | يحدد URI المطلق من URI الأساسي و URIs النسبية. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/ar/aspose.slides.importing/externalresourceresolver/get_entity/#str) | يربط URI بكائن يحتوي على المورد الفعلي. |


### انظر أيضًا
* الوحدة [`aspose.slides.importing`](/slides/python-net/ar/aspose.slides.importing)
* المكتبة [`Aspose.Slides`](/slides/python-net)