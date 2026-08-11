---
title: CloneNode()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ نسخة مكررة من هذه العقدة.
type: docs
weight: 118
url: /ar/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) طريقة


ينشئ نسخة مكررة من هذه العقدة.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| deep | **bool** | **true** لتكرار استنساخ الشجرة الفرعية تحت العقدة المحددة؛ **false** لاستنساخ العقدة نفسها فقط. بالنسبة لعقد نوع المستند، العقدة المستنسخة تشمل الشجرة الفرعية دائمًا، بغض النظر عن إعداد المعامل. |

### قيمة الإرجاع

العقدة المستنسخة.

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlDocumentType](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)