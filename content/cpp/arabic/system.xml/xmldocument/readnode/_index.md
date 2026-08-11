---
title: ReadNode()
second_title: Aspose.Slides لمرجع API C++
description: إنشاء كائن XmlNode بناءً على المعلومات الموجودة في XmlReader. يجب أن يكون القارئ موجهًا إلى عقدة أو سمة.
type: docs
weight: 495
url: /ar/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) طريقة

ينشئ كائنًا من [XmlNode](../../xmlnode/) بناءً على المعلومات في [XmlReader](../../xmlreader/). يجب أن يكون القارئ موجهًا إلى عقدة أو سمة.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | مصدر XML. |

### قيمة الإرجاع

الكائن الجديد [XmlNode](../../xmlnode/) أو **nullptr** إذا لم تعد هناك عقد أخرى.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlReader](../../xmlreader/)
* فئة [XmlDocument](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)