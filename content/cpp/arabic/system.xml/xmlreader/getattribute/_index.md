---
title: GetAttribute()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات القيمة المحددة XmlReader::get_Name."
type: docs
weight: 599
url: /ar/system.xml/xmlreader/getattribute/
---
## طريقة XmlReader::GetAttribute(String) method

عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات القيمة [XmlReader::get_Name](../get_name/) المحددة.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للسمة. |

### قيمة الإرجاع

قيمة السمة المحددة. إذا لم يتم العثور على السمة أو كانت القيمة [String::Empty](../../../system/string/empty/)، يتم إرجاع **nullptr**.

## طريقة XmlReader::GetAttribute(String, String) method

عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات القيمتين [XmlReader::get_LocalName](../get_localname/) و[XmlReader::get_NamespaceURI](../get_namespaceuri/) المحددتين.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المحلي للسمة. |
| namespaceURI | [String](../../../system/string/) | معرف مساحة الاسم للسمة. |

### قيمة الإرجاع

قيمة السمة المحددة. إذا لم يتم العثور على السمة أو كانت القيمة [String::Empty](../../../system/string/empty/)، يتم إرجاع **nullptr**. لا تقوم هذه الطريقة بتحريك القارئ.

## طريقة XmlReader::GetAttribute(int32_t) method

عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات الفهرس المحدد.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | **int32_t** | فهرس السمة. الفهرس يبدأ من الصفر. (السمة الأولى لها الفهرس 0.) |

### قيمة الإرجاع

قيمة السمة المحددة. لا تقوم هذه الطريقة بتحريك القارئ.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../)
* المجال [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)