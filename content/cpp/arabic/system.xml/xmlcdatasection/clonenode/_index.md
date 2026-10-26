---
title: CloneNode()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ نسخة مكررة من هذه العقدة.
type: docs
weight: 53
url: /ar/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) طريقة

يُنشئ نسخة مكررة من هذه العقدة.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| deep | **bool** | **true** لإستنساخ الشجرة الفرعية بشكل متكرر تحت العقدة المحددة؛ **false** لاستنساخ العقدة نفسها فقط. لأن عقد CDATA لا تحتوي على أبناء، بغض النظر عن إعداد المعامل، فإن العقدة المستنسخة ستتضمن دائمًا محتوى البيانات. |

### قيمة الإرجاع

العقدة المستنسخة.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlCDataSection](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)