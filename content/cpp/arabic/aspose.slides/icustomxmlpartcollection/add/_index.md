---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف جزء XML مخصص جديد.
type: docs
weight: 14
url: /ar/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) طريقة


يضيف جزء XML مخصص جديد.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بيانات XML للجزء الجديد الذي سيتم إضافته. |

### قيمة الإرجاع

تم إنشاء جزء XML مخصص.

## ICustomXmlPartCollection::Add(System::String) طريقة


يضيف جزء XML مخصص جديد.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | سلسلة XML للجزء الجديد الذي سيتم إضافته. |

### قيمة الإرجاع

تم إنشاء جزء XML مخصص.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) طريقة


يضيف جزء XML مخصص جديد.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق الإدخال الذي يحتوي على بيانات XML للجزء الجديد الذي سيتم إضافته. |

### قيمة الإرجاع

تم إنشاء جزء XML مخصص.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomXmlPart](../../icustomxmlpart/)
* Class [ICustomXmlPartCollection](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)