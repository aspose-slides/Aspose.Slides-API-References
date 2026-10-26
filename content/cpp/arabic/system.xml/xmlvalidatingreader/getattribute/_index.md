---
title: GetAttribute()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بإرجاع قيمة الخاصية ذات الاسم المحدد.
type: docs
weight: 443
url: /ar/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) طريقة

يعيد قيمة الخاصية ذات الاسم المحدد.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للخاصية. |

### قيمة الإرجاع

قيمة الخاصية المحددة. إذا لم يتم العثور على الخاصية، يتم إرجاع **nullptr**.

## XmlValidatingReader::GetAttribute(String, String) طريقة

يعيد قيمة الخاصية ذات الاسم المحلي ومعرف الموارد الموحد (URI) للمساحة الاسمية المحددة.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للخاصية. |
| namespaceURI | [String](../../../system/string/) | معرف URI للمساحة الاسمية للخاصية. |

### قيمة الإرجاع

قيمة الخاصية المحددة. إذا لم يتم العثور على الخاصية، يتم إرجاع **nullptr**. هذه الطريقة لا تحرك القارئ.

## XmlValidatingReader::GetAttribute(int32_t) طريقة

يعيد قيمة الخاصية ذات الفهرس المحدد.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | **int32_t** | الفهرس للخاصية. الفهرس يبدأ من الصفر. (الخاصية الأولى لها فهرس 0.) |

### قيمة الإرجاع

قيمة الخاصية المحددة.

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [XmlValidatingReader](../)
* مجال الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)