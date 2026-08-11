---
title: CloneNode()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ نسخة مكررة من هذه العقدة.
type: docs
weight: 92
url: /ar/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) طريقة

ينشئ نسخة مكررة من هذه العقدة.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| deep | **bool** | **true** لتنسخ الشجرة الفرعية تحت العقدة المحددة بشكل متكرر؛ **false** لتنسخ العقدة نفسها فقط. بالنسبة لعقد [XmlEntityReference](../)، هذه الطريقة تُعيد دائمًا عقدة إشارة كيان بدون أبناء. يتم تعيين نص الاستبدال عندما تُدرج العقدة في أب. |

### قيمة الإرجاع

العقدة المستنسخة.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlEntityReference](../)
* مساحة الاسم [System::Xml](../../)
* Library [Aspose.Slides](../../../)