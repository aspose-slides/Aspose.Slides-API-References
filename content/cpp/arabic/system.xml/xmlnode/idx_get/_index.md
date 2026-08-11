---
title: idx_get()
second_title: Aspose.Slides للـ C++ مرجع API
description: "يرجع العنصر الفرعي الأول مع XmlNode::get_Name المحدد."
type: docs
weight: 586
url: /ar/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) طريقة

يرجع العنصر الفرعي الأول الذي يطابق [XmlNode::get_Name](../get_name/) المحدد.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### المتغيرات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للعنصر المراد استرداده. |

### قيمة الإرجاع

العنصر الأول [XmlElement](../../xmlelement/) الذي يطابق الاسم المحدد. يُرجع **nullptr** إذا لم يكن هناك تطابق.

## XmlNode::idx_get(String, String) طريقة

يرجع العنصر الفرعي الأول الذي يطابق القيم المحددة [XmlNode::get_LocalName](../get_localname/) و [XmlNode::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### المتغيرات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localname | [String](../../../system/string/) | الاسم المحلي للعنصر. |
| ns | [String](../../../system/string/) | معرّف مساحة الاسم للعنصر. |

### قيمة الإرجاع

العنصر الأول [XmlElement](../../xmlelement/) الذي يطابق **localname** و **ns**. يُرجع **nullptr** إذا لم يكن هناك تطابق.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [XmlElement](../../xmlelement/)
* الفئة [String](../../../system/string/)
* الفئة [XmlNode](../)
* مساحة الاسم [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)