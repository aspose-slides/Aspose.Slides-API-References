---
title: WriteProcessingInstruction()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يكتب تعليمة معالجة مع وجود مسافة بين الاسم والنص كما يلي: <?name text?>."
type: docs
weight: 326
url: /ar/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) method

يكتب تعليمة معالجة مع وجود مسافة بين الاسم والنص كما يلي: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم تعليمة المعالجة. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) لتضمينه في تعليمة المعالجة. |
## ملاحظات

يتم استخدام هذه الطريقة لإنشاء إعلان XML بعد أن تم استدعاء [XmlTextWriter::WriteStartDocument](../writestartdocument/) بالفعل.
## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlTextWriter](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)