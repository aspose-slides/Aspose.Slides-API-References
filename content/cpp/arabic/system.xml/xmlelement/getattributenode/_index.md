---
title: GetAttributeNode()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعيد XmlAttribute بالاسم المحدد.
type: docs
weight: 248
url: /ar/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) طريقة

يعيد [XmlAttribute](../../xmlattribute/) بالاسم المحدد.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية المراد استردادها. هذا اسم مؤهل. يتم مطابقته مع قيمة **get_Name** للعنصر المطابق. |

### قيمة الإرجاع

الـ [XmlAttribute](../../xmlattribute/) المحدد أو **nullptr** إذا لم يتم العثور على خاصية مطابقة.

## XmlElement::GetAttributeNode(String, String) طريقة

يعيد [XmlAttribute](../../xmlattribute/) بالاسم المحلي المحدد ومعرّف مساحة الاسم.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للخاصية. |
| namespaceURI | [String](../../../system/string/) | معرّف مساحة الاسم للخاصية. |

### قيمة الإرجاع

الـ [XmlAttribute](../../xmlattribute/) المحدد أو **nullptr** إذا لم يتم العثور على خاصية مطابقة.

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlAttribute](../../xmlattribute/)
* فئة [String](../../../system/string/)
* فئة [XmlElement](../)
* فضاء الأسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)