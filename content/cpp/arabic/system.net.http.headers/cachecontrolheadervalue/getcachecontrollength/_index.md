---
title: GetCacheControlLength()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتحويل سلسلة مُمرَّرة من الفهرس المحدد إلى نسخة من فئة CacheControlHeaderValue.
type: docs
weight: 456
url: /ar/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) طريقة

يقوم بتحويل سلسلة مُمرَّرة من الفهرس المحدد إلى نسخة من الفئة [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة للتحليل. |
| startIndex | **int32_t** | موضع بدء التحليل. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | قيمة يجب إضافتها إلى الكائن المُحلَّل. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | نسخة سيتم تعيين الكائن المُحلَّل إليها. |

### قيمة الإرجاع

طول الجزء الفرعي المُحلَّل، وإلا 0.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [CacheControlHeaderValue](../)
* مساحة اسم [System::Net::Http::Headers](../../)
* مكتبة [Aspose.Slides](../../../)