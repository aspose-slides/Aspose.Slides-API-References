---
title: ReadAttributeValue()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحليل قيمة السمة إلى واحدة أو أكثر من عقد Text أو EntityReference أو EndEntity.
type: docs
weight: 560
url: /ar/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() طريقة

يقوم بتحليل قيمة السمة إلى واحد أو أكثر من العقد **[Text](../../../system.text/)**، **EntityReference**، أو **EndEntity**.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### قيمة الإرجاع

**true** إذا كان هناك عقد للعودة. **false** إذا لم يكن القارئ موجهًا إلى عقدة سمة عند الاستدعاء الأول أو إذا تم قراءة جميع قيم السمات. سمة فارغة، مثل **misc=\"\"**، تُعيد **true** مع عقدة واحدة ذات قيمة [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* الفئة [XmlTextReader](../)
* المساحة الاسمية [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)