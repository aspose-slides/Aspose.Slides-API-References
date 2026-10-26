---
title: CreateAttribute()
second_title: Aspose.Slides للـ C++ مرجع API
description: ينشئ XmlAttribute بالاسم المحدد.
type: docs
weight: 274
url: /ar/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) طريقة

ينشئ [XmlAttribute](../../xmlattribute/) بالاسم المحدد.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | الاسم المؤهل للخاصية. إذا كان الاسم يحتوي على نقطتين، فإن قيمة [XmlNode::get_Prefix](../../xmlnode/get_prefix/) تعكس الجزء من الاسم الذي يسبق النقطتين الأوليين وقيمة [XmlDocument::get_LocalName](../get_localname/) تعكس الجزء من الاسم الذي يلي النقطتين. يبقى [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) فارغًا ما لم يكن البrefix هو بادئة مدمجة معروفة مثل **xmlns**. في هذه الحالة يكون لـ get_NamespaceURI قيمة [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### قيمة الإرجاع

الـ [XmlAttribute](../../xmlattribute/) الجديد.

## XmlDocument::CreateAttribute(const String\&, const String\&) طريقة

ينشئ [XmlAttribute](../../xmlattribute/) بالاسم المؤهل المحدد و[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | الاسم المؤهل للخاصية. إذا كان الاسم يحتوي على نقطتين فإن قيمة [XmlNode::get_Prefix](../../xmlnode/get_prefix/) ستعكس الجزء من الاسم الذي يسبق النقطتين وقيمة [XmlDocument::get_LocalName](../get_localname/) ستعكس الجزء من الاسم الذي يلي النقطتين. |
| namespaceURI | const [String](../../../system/string/)\& | مسافة الاسم (namespaceURI) للخاصية. إذا كان الاسم المؤهل يتضمن بادئة **xmlns**، فيجب أن تكون هذه المعلمة [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### قيمة الإرجاع

الـ [XmlAttribute](../../xmlattribute/) الجديد.

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) طريقة

ينشئ [XmlAttribute](../../xmlattribute/) بالـ [XmlNode::get_Prefix](../../xmlnode/get_prefix/) المحدد، [XmlDocument::get_LocalName](../get_localname/)، و[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | بادئة الخاصية (إن وجدت). [String::Empty](../../../system/string/empty/) و **nullptr** متكافئان. |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للخاصية. |
| namespaceURI | const [String](../../../system/string/)\& | مسافة اسم (namespace URI) للخاصية (إن وجدت). [String::Empty](../../../system/string/empty/) و **nullptr** متكافئان. إذا كانت **prefix** هي **xmlns**، فيجب أن تكون هذه المعلمة [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) وإلا سيتم رفع استثناء. |

### قيمة الإرجاع

الـ [XmlAttribute](../../xmlattribute/) الجديد.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlAttribute](../../xmlattribute/)
* فئة [String](../../../system/string/)
* فئة [XmlDocument](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)