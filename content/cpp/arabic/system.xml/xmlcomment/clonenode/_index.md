---
title: CloneNode()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نسخة مكررة من هذه العقدة.
type: docs
weight: 40
url: /ar/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) الطريقة

ينشئ نسخة مكررة من هذه العقدة.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| deep | **bool** | **true** لاستنساخ شجرة فرعية تحت العقدة المحددة بشكل متكرر؛ **false** لاستنساخ العقدة نفسها فقط. نظرًا لأن عقد التعليقات لا تحتوي على أطفال، فإن العقدة المستنسخة دائمًا ما تتضمن المحتوى النصي، بغض النظر عن إعداد المعامل. |

### قيمة الإرجاع

العقدة المستنسخة.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlComment](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)