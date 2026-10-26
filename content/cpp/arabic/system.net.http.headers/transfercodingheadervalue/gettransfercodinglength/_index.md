---
title: GetTransferCodingLength()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتحويل سلسلة مُمرَّرة من الفهرس المحدد إلى كائن من فئة TransferCodingHeaderValue.
type: docs
weight: 105
url: /ar/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) طريقة

يقوم بتحويل سلسلة مُمرَّرة من الفهرس المحدد إلى كائن من فئة [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة للتحليل. |
| startIndex | **int32_t** | موضع البداية للتحليل. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | كائن سيتم تعيين الكائن المُحلَّل إليه. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | المندوب الذي يُستخدم لإنشاء كائنات من فئة [TransferCodingHeaderValue](../). |

### قيمة الإرجاع

يرجع طول الجزء الفرعي المُحلَّل، وإلا 0.

## انظر أيضاً

* تعريف نوع [HeaderFunc](../../headerfunc/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [TransferCodingHeaderValue](../)
* نطاق [System::Net::Http::Headers](../../)
* مكتبة [Aspose.Slides](../../../)