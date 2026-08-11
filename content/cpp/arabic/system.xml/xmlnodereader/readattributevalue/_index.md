---
title: ReadAttributeValue()
second_title: Aspose.Slides للـ C++ مرجع API
description: يقوم بتحليل قيمة السمة إلى واحد أو أكثر من عقد Text أو EntityReference أو EndEntity.
type: docs
weight: 430
url: /ar/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() طريقة

يقوم بتحليل قيمة السمة إلى واحد أو أكثر من **[Text](../../../system.text/)**، **EntityReference**، أو **EndEntity**.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### قيمة الإرجاع

**true** إذا كان هناك عقد للعودة. **false** إذا لم يكن القارئ موضعًا على عقدة سمة عند إجراء الاستدعاء الأولي أو إذا تم قراءة جميع قيم السمات. سمة فارغة، مثل **misc=\"\"**، تُعيد **true** مع عقدة واحدة قيمتها [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* الفئة [XmlNodeReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)