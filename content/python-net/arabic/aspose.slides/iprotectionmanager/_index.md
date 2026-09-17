---
title: IProtectionManager class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/iprotectionmanager/
---
## IProtectionManager فئة

إدارة حماية كلمة مرور العرض التقديمي.

نوع IProtectionManager يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/ar/aspose.slides/iprotectionmanager/encrypt_document_properties/) | هذه الخاصية لها معنى إذا كان العرض التقديمي محميًا بكلمة مرور.<br/>            إذا كان true فإن خصائص المستند مشفّرة في ملف العرض.<br/>            إذا كان false فإن خصائص المستند عامة بينما يكون العرض مشفّراً.<br/>            قراءة/كتابة **bool**. |
| [`is_encrypted`](/slides/python-net/ar/aspose.slides/iprotectionmanager/is_encrypted/) | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة مشفرة.<br/>            قراءة فقط **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/ar/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | هذه الخاصية لها معنى إذا كان ملف العرض محميًا بكلمة مرور وخصائص المستند لهذا الملف عامة.<br/>            القيمة true تعني أن خصائص المستند فقط تم تحميلها من عرض مشفر بدون استخدام كلمة مرور.<br/>            القيمة false تعني أن العرض المشفر بالكامل تم تحميله باستخدام كلمة المرور الصحيحة، وليس فقط خصائص المستند.<br/>            إذا لم يكن العرض مشفرًا فإن قيمة الخاصية دائمًا false.<br/>            إذا لم تكن خصائص المستند لملف مشفر عامة فإن قيمة الخاصية دائمًا false.<br/>            إذا كان PresentationEx.EncryptDocumentProperties صحيحًا فإن قيمة IsOnlyDocumentPropertiesLoaded دائمًا false.<br/>            قراءة فقط **bool**. |
| [`is_write_protected`](/slides/python-net/ar/aspose.slides/iprotectionmanager/is_write_protected/) | يحصل على قيمة تشير إلى ما إذا كان هذا العرض محميًا من الكتابة.<br/>            قراءة فقط **bool**. |
| [`encryption_password`](/slides/python-net/ar/aspose.slides/iprotectionmanager/encryption_password/) | يعيد كلمة مرور التشفير.<br/>            قراءة فقط **str**. |
| [`read_only_recommended`](/slides/python-net/ar/aspose.slides/iprotectionmanager/read_only_recommended/) | يحصل على أو يضبط توصية القراءة فقط.<br/>            قراءة/كتابة **bool**. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/ar/aspose.slides/iprotectionmanager/encrypt/#str) | يشفر العرض التقديمي باستخدام كلمة مرور محددة. |
| [`remove_encryption(self)`](/slides/python-net/ar/aspose.slides/iprotectionmanager/remove_encryption/#) | يزيل التشفير. |
| [`set_write_protection(self, password)`](/slides/python-net/ar/aspose.slides/iprotectionmanager/set_write_protection/#str) | يحدد حماية الكتابة لهذا العرض باستخدام كلمة مرور محددة. |
| [`remove_write_protection(self)`](/slides/python-net/ar/aspose.slides/iprotectionmanager/remove_write_protection/#) | يزيل حماية الكتابة لهذا العرض. |
| [`check_write_protection(self, password)`](/slides/python-net/ar/aspose.slides/iprotectionmanager/check_write_protection/#str) | يحدد ما إذا كان العرض محميًا بكلمة مرور للتعديل. |


### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)