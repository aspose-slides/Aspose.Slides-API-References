---
title: MoveToAttribute()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينتقل إلى السمة ذات الاسم المحدد.
type: docs
weight: 300
url: /ar/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) طريقة

ينتقل إلى السمة ذات الاسم المحدد.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للسمة. |

### قيمة الإرجاع

**true** إذا تم العثور على السمة; وإلا **false**. إذا **false** لا يتغير موضع القارئ.

## XmlNodeReader::MoveToAttribute(String, String) طريقة

ينتقل إلى السمة ذات الاسم المحلي المحدد وURI مساحة الاسم.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المحلي للسمة. |
| namespaceURI | [String](../../../system/string/) | URI مساحة الاسم للسمة. |

### قيمة الإرجاع

**true** إذا تم العثور على السمة; وإلا **false**. إذا **false** لا يتغير موضع القارئ.

## XmlNodeReader::MoveToAttribute(int32_t) طريقة

ينتقل إلى السمة ذات الفهرس المحدد.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| attributeIndex | **int32_t** | فهرس السمة. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNodeReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)