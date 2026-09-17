---
title: ProtectionManager class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/protectionmanager/
---
## ProtectionManager فئة

إدارة حماية كلمة مرور العرض التقديمي.

نوع ProtectionManager يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/ar/aspose.slides/protectionmanager/encrypt_document_properties/) | هذه الخاصية ذات معنى إذا كان العرض محميًا بكلمة مرور.<br/>            إذا كان صحيحًا فإن خصائص المستند مشفرة في ملف العرض.<br/>            إذا كان خطأً فإن خصائص المستند عامة بينما العرض مشفر.<br/>            قراءة/كتابة **bool**. |
| [`is_encrypted`](/slides/python-net/ar/aspose.slides/protectionmanager/is_encrypted/) | يُحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة مشفرة.<br/>            قراءة فقط **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/ar/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور وكانت خصائص المستند لهذا الملف عامة.<br/>            قيمة صحيح تعني أن خصائص المستند فقط يتم تحميلها من ملف عرض مشفر دون استخدام كلمة مرور.<br/>            قيمة خطأ تعني أن العرض المشفر بالكامل يتم تحميله باستخدام كلمة مرور صحيحة، وليس فقط خصائص المستند.<br/>            إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تكون دائمًا خاطئة.<br/>            إذا لم تكن خصائص المستند لملف مشفر عامة فإن قيمة الخاصية تكون دائمًا خاطئة.<br/>            إذا كان Presentation.EncryptDocumentProperties صحيحًا فإن قيمة IsOnlyDocumentPropertiesLoaded تكون دائمًا خاطئة.<br/>            قراءة فقط **bool**. |
| [`is_write_protected`](/slides/python-net/ar/aspose.slides/protectionmanager/is_write_protected/) | يُحصل على قيمة تشير إلى ما إذا كان هذا العرض محميًا من الكتابة.<br/>            قراءة فقط **bool**. |
| [`encryption_password`](/slides/python-net/ar/aspose.slides/protectionmanager/encryption_password/) | يُحصل على كلمة المرور المستخدمة لتشفير العرض.<br/>            قراءة فقط **str**. |
| [`read_only_recommended`](/slides/python-net/ar/aspose.slides/protectionmanager/read_only_recommended/) | يُحصل أو يُحدد توصية القراءة فقط.<br/>            قراءة/كتابة **bool**. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/ar/aspose.slides/protectionmanager/encrypt/#str) | يشفّر العرض باستخدام كلمة مرور محددة. |
| [`remove_encryption(self)`](/slides/python-net/ar/aspose.slides/protectionmanager/remove_encryption/#) | يزيل التشفير. |
| [`set_write_protection(self, password)`](/slides/python-net/ar/aspose.slides/protectionmanager/set_write_protection/#str) | يعيّن حماية كتابة لهذا العرض باستخدام كلمة مرور محددة. |
| [`remove_write_protection(self)`](/slides/python-net/ar/aspose.slides/protectionmanager/remove_write_protection/#) | يزيل حماية الكتابة لهذا العرض. |
| [`check_write_protection(self, password)`](/slides/python-net/ar/aspose.slides/protectionmanager/check_write_protection/#str) | يحدّد ما إذا كان العرض محميًا بكلمة مرور للتعديل. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)