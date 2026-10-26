---
title: ReadAttributeValue()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحليل قيمة السمة إلى عقدة أو أكثر من نوع Text أو EntityReference أو EndEntity.
type: docs
weight: 508
url: /ar/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() طريقة

يقوم بتحليل قيمة السمة إلى واحد أو أكثر من **[Text](../../../system.text/)**, **EntityReference**, أو **EndEntity** عقد.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### قيمة الإرجاع

**true** إذا كان هناك عقد لإرجاعها. **false** إذا لم يكن القارئ موضعه على عقدة سمة عند إجراء النداء الأولي أو إذا تم قراءة جميع قيم السمات. سمة فارغة، مثل **misc=\"\"**، تُعيد **true** مع عقدة واحدة بقيمة [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* الفئة [XmlValidatingReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)