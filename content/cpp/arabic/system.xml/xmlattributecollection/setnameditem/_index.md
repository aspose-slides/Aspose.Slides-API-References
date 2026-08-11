---
title: SetNamedItem()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يضيف عقدة XmlNode باستخدام نتيجة XmlNode::get_Name الخاصة بها."
type: docs
weight: 14
url: /ar/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) طريقة

يضيف [XmlNode](../../xmlnode/) باستخدام نتيجته [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | عقدة صفة يتم تخزينها في هذه المجموعة. ستصبح العقدة قابلة للوصول لاحقًا باستخدام اسم العقدة. إذا كانت هناك عقدة بهذا الاسم موجودة بالفعل في المجموعة، فسيتم استبدالها بالعقدة الجديدة؛ وإلا، تُضاف العقدة إلى نهاية المجموعة. |

### Return Value

إذا كان **node** يستبدل عقدة موجودة بنفس الاسم، يتم إرجاع العقدة القديمة؛ وإلا، يتم إرجاع العقدة المضافة.

## See Also

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlAttributeCollection](../)
* نطاق الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)