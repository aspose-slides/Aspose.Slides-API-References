---
title: CloneNode()
second_title: Aspose.Slides مرجع API لـ C++
description: ينشئ نسخة مكررة من هذه العقدة. لا يمكن استنساخ عقد النوتة. استدعاء هذه الطريقة على كائن XmlNotation يؤدي إلى رمي استثناء.
type: docs
weight: 118
url: /ar/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) طريقة

ينشئ نسخة مكررة من هذه العقدة. لا يمكن استنساخ عقد النوتة. استدعاء هذه الطريقة على كائن [XmlNotation](../) يؤدي إلى رمية استثناء.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| deep | **bool** | **true** لاستنساخ الشجرة الفرعية تحت العقدة المحددة بشكل متكرر؛ **false** لاستنساخ العقدة نفسها فقط. |

### قيمة الإرجاع

نسخة [XmlNode](../../xmlnode/) من العقدة التي تم استدعاء الطريقة عليها.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlNotation](../)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)