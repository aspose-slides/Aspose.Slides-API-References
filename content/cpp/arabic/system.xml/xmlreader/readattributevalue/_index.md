---
title: ReadAttributeValue()
second_title: Aspose.Slides للغة C++ مرجع API
description: عند تجاوزها في صف مشتق، تقوم بتحليل قيمة السمة إلى واحد أو أكثر من عقد Text أو EntityReference أو EndEntity.
type: docs
weight: 677
url: /ar/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() طريقة

عند تجاوزها في صف مُشتق، تحلل قيمة السمة إلى واحد أو أكثر من **[Text](../../../system.text/)** ، **EntityReference** أو **EndEntity** عقد.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### قيمة الإرجاع

**true** إذا كانت هناك عقد لإرجاعها. **false** إذا لم يكن القارئ موضعًا على عقدة سمة عند إجراء النداء الأول أو إذا تم قراءة جميع قيم السمات. سمة فارغة، مثل **misc=""**، تُعيد **true** بعقدة واحدة ذات قيمة [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* الفئة [XmlReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)