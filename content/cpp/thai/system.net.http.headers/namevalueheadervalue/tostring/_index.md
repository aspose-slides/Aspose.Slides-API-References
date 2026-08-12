---
title: ToString()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คล้ายกับเมธอด C# Object.ToString() ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้.
type: docs
weight: 79
url: /th/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const เมธอด

คล้ายกับเมธอด C# [Object.ToString()](../../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### ค่าที่ส่งคืน

[String](../../../system/string/) การแสดงผลตามที่คลาสสุดท้ายให้มา.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) เมธอด

คืนค่าการแสดงผลสตริงของคอลเลกชันของอินสแตนซ์คลาส NameValueHeaderValue.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | คอลเลกชันของอินสแตนซ์คลาส NameValueHeaderValue. |
| separator | char16_t | ตัวคั่นสตริง. |
| leadingSeparator | **bool** | ค่าที่บ่งชี้ว่าตัวคั่นสตริงต้องถูกเพิ่มก่อนรายการแรกของคอลเลกชันหรือไม่. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | อินสแตนซ์ที่การแสดงผลสตริงจะถูกกำหนดค่าให้. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) เมธอด

คืนค่าการแสดงผลสตริงของคอลเลกชันของอินสแตนซ์คลาส NameValueHeaderValue.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | คอลเลกชันของอินสแตนซ์คลาส NameValueHeaderValue. |
| separator | char16_t | ตัวคั่นสตริง. |
| leadingSeparator | **bool** | ค่าที่บ่งชี้ว่าตัวคั่นสตริงต้องถูกเพิ่มก่อนรายการแรกของคอลเลกชันหรือไม่. |

### ค่าที่ส่งคืน

การแสดงผลสตริงของคอลเลกชันของอินสแตนซ์คลาส NameValueHeaderValue.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [NameValueHeaderValue](../)
* คลาส [ObjectCollection](../../objectcollection/)
* คลาส [StringBuilder](../../../system.text/stringbuilder/)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)