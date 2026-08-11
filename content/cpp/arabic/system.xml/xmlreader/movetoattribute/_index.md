---
title: MoveToAttribute()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "عند تجاوزها في فئة مشتقة، ينتقل إلى السمة التي لها القيمة المحددة XmlReader::get_Name."
type: docs
weight: 625
url: /ar/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) method

عند تجاوزها في فئة مشتقة، ينتقل إلى السمة التي لها القيمة المحددة [XmlReader::get_Name](../get_name/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للخاصية. |

### قيمة الإرجاع

**true** إذا تم العثور على السمة؛ وإلا **false**. إذا كان **false**، فإن موضع القارئ لا يتغير.

## XmlReader::MoveToAttribute(String, String) method

عند تجاوزها في فئة مشتقة، ينتقل إلى السمة التي لها القيم المحددة [XmlReader::get_LocalName](../get_localname/) و[XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المحلي للخاصية. |
| ns | [String](../../../system/string/) | معرف URI للمساحة الاسمية للخاصية. |

### قيمة الإرجاع

**true** إذا تم العثور على السمة؛ وإلا **false**. إذا كان **false**، فإن موضع القارئ لا يتغير.

## XmlReader::MoveToAttribute(int32_t) method

عند تجاوزها في فئة مشتقة، ينتقل إلى السمة التي لها الفهرس المحدد.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | **int32_t** | فهرس الخاصية. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)