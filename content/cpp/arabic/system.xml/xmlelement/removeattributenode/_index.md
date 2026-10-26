---
title: RemoveAttributeNode()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يزيل XmlAttribute المحدد.
type: docs
weight: 274
url: /ar/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) طريقة


يزيل [XmlAttribute](../../xmlattribute/) المحدد.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | العقدة [XmlAttribute](../../xmlattribute/) لإزالتها. إذا كان للخاصية المُزالة قيمة افتراضية، يتم استبدالها فوراً. |

### قيمة الإرجاع

العنصر [XmlAttribute](../../xmlattribute/) المُزال أو **nullptr** إذا لم يكن **oldAttr** عقدة خاصية في [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) طريقة


يزيل [XmlAttribute](../../xmlattribute/) المحدد بالاسم المحلي ومعرف مساحة الاسم. (إذا كان للخاصية المُزالة قيمة افتراضية، يتم استبدالها فوراً).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للخاصية. |
| namespaceURI | [String](../../../system/string/) | معرف مساحة الاسم للخاصية. |

### قيمة الإرجاع

العنصر [XmlAttribute](../../xmlattribute/) المُزال أو **nullptr** إذا لم يكن لدى [XmlElement](../) عقدة خاصية مطابقة.

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlAttribute](../../xmlattribute/)
* فئة [XmlElement](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)