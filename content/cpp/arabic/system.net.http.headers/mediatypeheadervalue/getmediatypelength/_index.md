---
title: GetMediaTypeLength()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يحوّل السلسلة الممرّرة من الفهرس المحدد إلى كائن من فئة MediaTypeHeaderValue.
type: docs
weight: 144
url: /ar/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) طريقة

تحول السلسلة المُمرَّرة من الفهرس المحدد إلى كائن من الفئة [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة للتحليل. |
| startIndex | **int32_t** | موضع بدء للتحليل. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | المفوّض المستخدم لإنشاء كائنات من الفئة [MediaTypeHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | كائن سيتم تعيين الكائن المحلل إليه. |

### قيمة الإرجاع

يعيد طول الجزء الفرعي المحلل، وإلا 0.

## انظر أيضًا

* تعريف نوع [HeaderFunc](../../headerfunc/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [MediaTypeHeaderValue](../)
* فضاء الاسم [System::Net::Http::Headers](../../)
* مكتبة [Aspose.Slides](../../../)