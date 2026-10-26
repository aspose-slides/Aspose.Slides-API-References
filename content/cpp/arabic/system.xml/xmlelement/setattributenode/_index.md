---
title: SetAttributeNode()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف XmlAttribute المحدد.
type: docs
weight: 261
url: /ar/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) طريقة

يضيف [XmlAttribute](../../xmlattribute/) المحدد.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### وسائط

| معاملة | نوع | وصف |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | العقدة [XmlAttribute](../../xmlattribute/) لإضافتها إلى مجموعة السمات لهذا العنصر. |

### قيمة الإرجاع

إذا كان السمة تستبدل سمة موجودة بنفس الاسم، يُرجَع [XmlAttribute](../../xmlattribute/) القديم؛ وإلا، يُرجَع **nullptr**.

## XmlElement::SetAttributeNode(String, String) طريقة

يضيف [XmlAttribute](../../xmlattribute/) المحدد.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### وسائط

| معاملة | نوع | وصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للخاصية. |
| namespaceURI | [String](../../../system/string/) | عنوان URI للمساحة الاسمية للخاصية. |

### قيمة الإرجاع

ال[XmlAttribute](../../xmlattribute/) للإضافة.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlAttribute](../../xmlattribute/)
* فئة [XmlElement](../)
* فئة [String](../../../system/string/)
* مساحة أسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)