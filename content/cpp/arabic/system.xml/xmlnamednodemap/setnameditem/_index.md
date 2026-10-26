---
title: SetNamedItem()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يضيف XmlNode باستخدام قيمة XmlNode::get_Name الخاصة به."
type: docs
weight: 27
url: /ar/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) طريقة

يضيف [XmlNode](../../xmlnode/) باستخدام قيمة [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) لتخزينه في [XmlNamedNodeMap](../). إذا كانت عقدة بهذا الاسم موجودة بالفعل في الخريطة، فسيتم استبدالها بالجديدة. |

### قيمة الإرجاع

إذا كان **node** يستبدل عقدة موجودة بنفس الاسم، يتم إرجاع العقدة القديمة؛ وإلا يتم إرجاع **nullptr**.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlNamedNodeMap](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)