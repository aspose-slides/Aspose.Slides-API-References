---
title: MoveToAttribute()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينتقل إلى السمة ذات الاسم المحدد.
type: docs
weight: 508
url: /ar/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) طريقة

تنتقل إلى السمة ذات الاسم المحدد.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للسمة. |

### قيمة الإرجاع

**true** إذا تم العثور على السمة؛ وإلا **false**. إذا **false**، لا يتغير موضع القارئ.

## XmlTextReader::MoveToAttribute(String, String) طريقة

تنتقل إلى السمة ذات الاسم المحلي المحدد ومسار الـ URI للمساحة الاسمية.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للسمة. |
| namespaceURI | [String](../../../system/string/) | مسار الـ URI للمساحة الاسمية للسمة. |

### قيمة الإرجاع

**true** إذا تم العثور على السمة؛ وإلا **false**. إذا **false**، لا يتغير موضع القارئ.

## XmlTextReader::MoveToAttribute(int32_t) طريقة

تنتقل إلى السمة ذات الفهرس المحدد.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | **int32_t** | فهرس السمة. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlTextReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)