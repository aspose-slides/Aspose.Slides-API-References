---
title: idx_get()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع السمة ذات الفهرس المحدد.
type: docs
weight: 1
url: /ar/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) method


يرجع السمة ذات الفهرس المحدد.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | **int32_t** | فهرس السمة. |

### قيمة الإرجاع

السمة عند الفهرس المحدد.

## XmlAttributeCollection::idx_get(const String\&) method


يرجع السمة ذات الاسم المحدد.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | الاسم المؤهل للسمة. |

### قيمة الإرجاع

السمة ذات الاسم المحدد. إذا لم توجد السمة، تُعيد هذه الطريقة **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) method


يرجع السمة ذات الاسم المحلي ومسار URI للفضاء الاسمي (URI) المحددين.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للسمة. |
| namespaceURI | const [String](../../../system/string/)\& | مسار URI الخاص بالفضاء الاسمي للسمة. |

### قيمة الإرجاع

السمة ذات الاسم المحلي ومسار URI للفضاء الاسمي المحددين. إذا لم توجد السمة، تُعيد هذه الطريقة **nullptr**.

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlAttribute](../../xmlattribute/)
* فئة [XmlAttributeCollection](../)
* فئة [String](../../../system/string/)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)