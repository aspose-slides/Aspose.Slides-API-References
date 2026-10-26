---
title: GetAttribute()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع قيمة الخاصية بالاسم المحدد.
type: docs
weight: 287
url: /ar/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) طريقة

يرجع قيمة الخاصية بالاسم المحدد.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للخاصية. |

### قيمة الإرجاع

قيمة الخاصية المحددة. إذا لم يتم العثور على الخاصية، يتم إرجاع **nullptr**.

## XmlNodeReader::GetAttribute(String, String) طريقة

يرجع قيمة الخاصية بالاسم المحلي ومسار URI للمساحة الاسمية المحددين.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المحلي للخاصية. |
| namespaceURI | [String](../../../system/string/) | مسار URI للمساحة الاسمية للخاصية. |

### قيمة الإرجاع

قيمة الخاصية المحددة. إذا لم يتم العثور على الخاصية، يتم إرجاع **nullptr**.

## XmlNodeReader::GetAttribute(int32_t) طريقة

يرجع قيمة الخاصية بالفهرس المحدد.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| attributeIndex | **int32_t** | فهرس الخاصية. الفهرس يبدأ من الصفر. (الخاصية الأولى لها الفهرس 0.) |

### قيمة الإرجاع

قيمة الخاصية المحددة.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNodeReader](../)
* المساحة الاسمية [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)