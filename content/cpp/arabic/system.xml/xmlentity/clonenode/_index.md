---
title: CloneNode()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نسخة مكررة من هذه العقدة. لا يمكن استنساخ عقد الكيان. استدعاء هذه الطريقة على كائن XmlEntity يطرح استثناءً.
type: docs
weight: 170
url: /ar/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) طريقة

ينشئ نسخة مكررة من هذا العقدة. لا يمكن استنساخ عقد الكيان. استدعاء هذه الطريقة على كائن [XmlEntity](../) يطرح استثناءً.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| deep | **bool** | **true** لاستنساخ الشجرة الفرعية تحت العقدة المحددة بشكلٍ متكرر؛ **false** لاستنساخ العقدة نفسها فقط. |

### قيمة الإرجاع

نسخة من [XmlNode](../../xmlnode/) التي تم استدعاء الطريقة منها.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlEntity](../)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)