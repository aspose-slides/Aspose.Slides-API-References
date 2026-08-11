---
title: MoveToAttribute()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينتقل إلى الخاصية ذات الاسم المحدد.
type: docs
weight: 456
url: /ar/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) طريقة

ينتقل إلى الخاصية ذات الاسم المحدد.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للخاصية. |

### قيمة الإرجاع

**true** إذا تم العثور على الخاصية؛ وإلا **false**. إذا كان **false**، لا يتغير موقع القارئ.

## XmlValidatingReader::MoveToAttribute(String, String) طريقة

ينتقل إلى الخاصية ذات الاسم المحلي المحدد ومعرف المورد الموحد للمساحة الاسمية (URI).

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للخاصية. |
| namespaceURI | [String](../../../system/string/) | معرف URI للمساحة الاسمية للخاصية. |

### قيمة الإرجاع

**true** إذا تم العثور على الخاصية؛ وإلا **false**. إذا كان **false**، لا يتغير موقع القارئ.

## XmlValidatingReader::MoveToAttribute(int32_t) طريقة

ينتقل إلى الخاصية ذات الفهرس المحدد.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | **int32_t** | فهرس الخاصية. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlValidatingReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)