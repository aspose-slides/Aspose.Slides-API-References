---
title: InsertBefore()
second_title: Aspose.Slides لمرجع API C++
description: يدرج العقدة المحددة مباشرةً قبل عقدة الإشارة المحددة.
type: docs
weight: 209
url: /ar/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) طريقة

يقوم بإدراج العقدة المحددة مباشرةً قبل عقدة الإشارة المحددة.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | ال[XmlNode](../../xmlnode/) للإدراج. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | ال[XmlNode](../../xmlnode/) التي هي عقدة الإشارة. **newChild** موضوعة قبل هذه العقدة. |

### قيمة الإرجاع

تم إدراج [XmlNode](../../xmlnode/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlAttribute](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)