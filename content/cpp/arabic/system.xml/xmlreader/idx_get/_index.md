---
title: idx_get()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند إعادة تعريفه في فئة مشتقة، يحصل على قيمة السمة ذات الفهرس المحدد.
type: docs
weight: 612
url: /ar/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) طريقة

عند إعادة تعريفه في فئة مشتقة، يحصل على قيمة السمة ذات الفهرس المحدد.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | **int32_t** | فهرس السمة. |

### قيمة الإرجاع

قيمة السمة المحددة.

## XmlReader::idx_get(String) طريقة

عند إعادة تعريفه في فئة مشتقة، يحصل على قيمة السمة ذات القيمة المحددة [XmlReader::get_Name](../get_name/).

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للسمة. |

### قيمة الإرجاع

قيمة السمة المحددة. إذا لم يتم العثور على السمة، يتم إرجاع **nullptr**.

## XmlReader::idx_get(String, String) طريقة

عند إعادة تعريفه في فئة مشتقة، يحصل على قيمة السمة ذات القيم المحددة [XmlReader::get_LocalName](../get_localname/) و [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المحلي للسمة. |
| namespaceURI | [String](../../../system/string/) | مسار URI للمجال الخاص بالسمة. |

### قيمة الإرجاع

قيمة السمة المحددة. إذا لم يتم العثور على السمة، يتم إرجاع **nullptr**.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)