---
title: WriteDocType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تقوم بكتابة تعريف DOCTYPE بالاسم المحدد والسمات الاختيارية.
type: docs
weight: 79
url: /ar/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) method

عند تجاوزها في فئة مشتقة، تقوم بكتابة تعريف DOCTYPE بالاسم المحدد والسمات الاختيارية.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم DOCTYPE. يجب أن يكون غير فارغ. |
| pubid | const [String](../../../system/string/)\& | إذا كان غير فارغ يكتب أيضًا PUBLIC "pubid" "sysid" حيث يتم استبدال **pubid** و **sysid** بقيمة الوسائط المعطاة. |
| sysid | const [String](../../../system/string/)\& | إذا كان **pubid** هو **nullptr** وكان **sysid** غير فارغ يكتب SYSTEM "sysid" حيث يتم استبدال **sysid** بقيمة هذا الوسيط. |
| subset | const [String](../../../system/string/)\& | إذا كان غير فارغ يكتب [subset] حيث يتم استبدال subset بقيمة هذا الوسيط. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlWriter](../)
* مساحة الاسم [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)