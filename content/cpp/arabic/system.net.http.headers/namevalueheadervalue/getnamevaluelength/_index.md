---
title: GetNameValueLength()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل سلسلة تم تمريرها من الفهرس المحدد إلى كائن من فئة NameValueHeaderValue.
type: docs
weight: 118
url: /ar/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) طريقة

يقوم بتحويل سلسلة مُمرَّرة من الفهرس المحدد إلى كائن من الفئة [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة للتحليل. |
| startIndex | **int32_t** | موضع البداية للتحليل. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | مثيل حيث سيتم تعيين الكائن المُحلَّل. |

### قيمة الإرجاع

يعيد طول الجزء الفرعي المُحلَّل، وإلا 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) طريقة

يقوم بتحويل سلسلة مُمرَّرة من الفهرس المحدد إلى كائن من الفئة [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة للتحليل. |
| startIndex | **int32_t** | موضع البداية للتحليل. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | دالة تُستخدم لإنشاء مثيلات جديدة من الفئة [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | مثيل حيث سيتم تعيين الكائن المُحلَّل. |

### قيمة الإرجاع

يعيد طول الجزء الفرعي المُحلَّل، وإلا 0.

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)