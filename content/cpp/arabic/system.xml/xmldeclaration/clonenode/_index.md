---
title: CloneNode()
second_title: Aspose.Slides لمرجع API للغة C++
description: ينشئ نسخة مكررة من هذه العقدة.
type: docs
weight: 157
url: /ar/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) طريقة

ينشئ نسخة مكررة من هذه العقدة.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| deep | **bool** | true لاستنساخ الشجرة الفرعية بشكل متكرر تحت العقدة المحددة؛ false لاستنساخ العقدة نفسها فقط. لأن [XmlDeclaration](../) لا تحتوي على أبناء، فإن العقدة المستنسخة تتضمن دائمًا قيمة البيانات، بغض النظر عن إعداد المعامل. |

### قيمة الإرجاع

العقدة المستنسخة.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [XmlNode](../../xmlnode/)
* الفئة [XmlDeclaration](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)