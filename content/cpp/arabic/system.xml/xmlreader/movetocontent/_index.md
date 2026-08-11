---
title: MoveToContent()
second_title: مرجع API Aspose.Slides للـ C++
description: "يتحقق مما إذا كان العنصر الحالي عقدة محتوى (نص غير مسافة بيضاء، CDATA، Element، EndElement، EntityReference، أو EndEntity). إذا لم تكن العقدة عقدة محتوى، يتخطى القارئ إلى عقدة المحتوى التالية أو إلى نهاية الملف. يتجاوز العقد من النوع التالي: ProcessingInstruction، DocumentType، Comment، Whitespace، أو SignificantWhitespace."
type: docs
weight: 833
url: /ar/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() طريقة

يتحقق مما إذا كان العنصر الحالي عقدة محتوى (نص غير مسافة بيضاء، **CDATA**، **Element**، **EndElement**، **EntityReference** أو **EndEntity**) . إذا لم تكن العقدة عقدة محتوى، يتخطى القارئ إلى العقدة المحتوى التالية أو إلى نهاية الملف. يتجاوز العقد من الأنواع التالية: **ProcessingInstruction**، **DocumentType**، **Comment**، **Whitespace** أو **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### قيمة الإرجاع

قيمة [XmlReader::get_NodeType](../get_nodetype/) للعقدة الحالية التي وجدت بواسطة الطريقة أو [XmlNodeType::None](../../xmlnodetype/) إذا وصل القارئ إلى نهاية تدفق الإدخال.

## انظر أيضًا

* التعداد [XmlNodeType](../../xmlnodetype/)
* الفئة [XmlReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)