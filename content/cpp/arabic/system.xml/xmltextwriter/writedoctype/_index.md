---
title: WriteDocType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يكتب بيان DOCTYPE بالاسم المحدد والسمات الاختيارية.
type: docs
weight: 222
url: /ar/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) طريقة

يكتب بيان DOCTYPE بالاسم المحدد والسمات الاختيارية.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم DOCTYPE. يجب أن يكون غير فارغ. |
| pubid | const [String](../../../system/string/)\& | إذا لم يكن null، فإنه يكتب أيضًا PUBLIC "pubid" "sysid" حيث يتم استبدال **pubid** و **sysid** بقيمة الحجج المعطاة. |
| sysid | const [String](../../../system/string/)\& | إذا كان **pubid** null وكان **sysid** غير null، فإنه يكتب SYSTEM "sysid" حيث يتم استبدال **sysid** بقيمة هذا الوسيط. |
| subset | const [String](../../../system/string/)\& | إذا لم يكن null فإنه يكتب [subset] حيث يتم استبدال subset بقيمة هذا الوسيط. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlTextWriter](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)