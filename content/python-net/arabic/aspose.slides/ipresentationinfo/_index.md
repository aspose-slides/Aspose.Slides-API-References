---
title: IPresentationInfo class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ipresentationinfo/
---
## IPresentationInfo فئة

معلومات حول ملف العرض التقديمي

نوع IPresentationInfo يكشف عن الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`is_encrypted`](/slides/python-net/ar/aspose.slides/ipresentationinfo/is_encrypted/) | يرجع True إذا كان العرض المرتبط مشفراً، وإلا False.<br/>            قراءة فقط **bool**. |
| [`is_password_protected`](/slides/python-net/ar/aspose.slides/ipresentationinfo/is_password_protected/) | يرجع قيمة تشير إلى ما إذا كان العرض المرتبط محمياً بكلمة مرور للفتح. |
| [`is_write_protected`](/slides/python-net/ar/aspose.slides/ipresentationinfo/is_write_protected/) | يرجع قيمة تشير إلى ما إذا كان العرض المرتبط محمياً من الكتابة. |
| [`load_format`](/slides/python-net/ar/aspose.slides/ipresentationinfo/load_format/) | يرجع تنسيق العرض المرتبط.<br/>            قراءة فقط [`LoadFormat`](/slides/python-net/ar/aspose.slides/loadformat). |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/ar/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | يكتب العرض المرتبط إلى تدفق. |
| [`write_binded_presentation(self, file)`](/slides/python-net/ar/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | يكتب العرض المرتبط إلى ملف. |
| [`check_password(self, password)`](/slides/python-net/ar/aspose.slides/ipresentationinfo/check_password/#str) | يتحقق مما إذا كانت كلمة المرور صحيحة للعرض المحمي بكلمة مرور الفتح. |
| [`check_write_protection(self, password)`](/slides/python-net/ar/aspose.slides/ipresentationinfo/check_write_protection/#str) | يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمي من الكتابة. |
| [`read_document_properties(self)`](/slides/python-net/ar/aspose.slides/ipresentationinfo/read_document_properties/#) | يحصل على خصائص المستند للعرض المرتبط. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/ar/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | يحدّث خصائص العرض المرتبط. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)