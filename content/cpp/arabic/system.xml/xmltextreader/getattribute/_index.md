---
title: GetAttribute()
second_title: Aspose.Slides للـ C++ مرجع API
description: تُرجع قيمة السمة ذات الاسم المحدد.
type: docs
weight: 495
url: /ar/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) طريقة

تُرجع قيمة السمة ذات الاسم المحدد.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للسمة. |

### قيمة الإرجاع

قيمة السمة المحددة. إذا لم يتم العثور على السمة، يتم إرجاع **nullptr**.

## XmlTextReader::GetAttribute(String, String) طريقة

تُرجع قيمة السمة ذات الاسم المحلي المحدد ومسار اسم الفضاء.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للسمة. |
| namespaceURI | [String](../../../system/string/) | مسار اسم الفضاء للسمة. |

### قيمة الإرجاع

قيمة السمة المحددة. إذا لم يتم العثور على السمة، يتم إرجاع **nullptr**. هذه الطريقة لا تحرك القارئ.

## XmlTextReader::GetAttribute(int32_t) طريقة

تُرجع قيمة السمة ذات الفهرس المحدد.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | فهرس السمة. الفهرس يبدأ من الصفر. (السمة الأولى لها فهرس 0.) |

### قيمة الإرجاع

قيمة السمة المحددة.

## راجع أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlTextReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)