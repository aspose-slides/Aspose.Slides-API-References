---
title: WriteProcessingInstruction()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "عند إلغاء التعريف في فئة مشتقة، يكتب تعليم معالجة مع مسافة بين الاسم والنص كما يلي: <?name text?>."
type: docs
weight: 196
url: /ar/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) طريقة

عند إلغاء التعريف في فئة مشتقة، يكتب تعليمًا معالجة مع مسافة بين الاسم والنص كما يلي: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم تعليم المعالجة. |
| text | [String](../../../system/string/) | النص المراد تضمينه في تعليم المعالجة. |
## ملاحظات

يتم استخدام هذه الطريقة لإنشاء إعلان XML بعد أن تم استدعاء [XmlWriter::WriteStartDocument](../writestartdocument/) بالفعل.
## انظر أيضاً

* الفئة [String](../../../system/string/)
* الفئة [XmlWriter](../)
* النطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)