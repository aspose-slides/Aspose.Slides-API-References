---
title: ToString()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مماثل لطريقة C# Object.ToString(). يتيح تحويل الكائنات المخصصة إلى سلسلة.
type: docs
weight: 79
url: /ar/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const طريقة

مماثل لطريقة C# [Object.ToString()](../../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### قيمة الإرجاع

[String](../../../system/string/) تمثيل كما توفره الفئة النهائية.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) طريقة

يعيد تمثيلًا نصيًا لمجموعة مثيلات فئة NameValueHeaderValue.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | مجموعة مثيلات فئة NameValueHeaderValue |
| separator | char16_t | فاصل نصي |
| leadingSeparator | **bool** | القيمة التي تحدد ما إذا كان يجب إضافة فاصل النص قبل العنصر الأول في المجموعة |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | مثيل سيُعيّن إليه تمثيل نصي |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) طريقة

يعيد تمثيلًا نصيًا لمجموعة مثيلات فئة NameValueHeaderValue.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | مجموعة مثيلات فئة NameValueHeaderValue |
| separator | char16_t | فاصل نصي |
| leadingSeparator | **bool** | القيمة التي تحدد ما إذا كان يجب إضافة فاصل النص قبل العنصر الأول في المجموعة |

### قيمة الإرجاع

تمثيل نصي لمجموعة مثيلات فئة NameValueHeaderValue.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [NameValueHeaderValue](../)
* فئة [ObjectCollection](../../objectcollection/)
* فئة [StringBuilder](../../../system.text/stringbuilder/)
* نطاق [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)