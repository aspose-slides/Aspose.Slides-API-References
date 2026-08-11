---
title: GetTransferCodingLength()
second_title: رفرنس API Aspose.Slides برای C++
description: رشته‌ی ارسال‌شده را از اندیس مشخص‌شده به یک نمونه از کلاس TransferCodingHeaderValue تبدیل می‌کند.
type: docs
weight: 105
url: /fa/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) متد

یک رشته‌ی ارسال‌شده را از اندیس مشخص‌شده به یک نمونه از کلاس [TransferCodingHeaderValue](../) تبدیل می‌کند.

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | [String](../../../system/string/) | یک رشته برای تجزیه. |
| startIndex | **int32_t** | یک موقعیت شروع برای تجزیه. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | یک نمونه‌ای که شی تجزیه‌شده در آن اختصاص خواهد یافت. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | نماینده‌ای که برای ایجاد نمونه‌های کلاس [TransferCodingHeaderValue](../) استفاده می‌شود. |

## مقدار بازگشتی

طول زیررشته تجزیه‌شده را برمی‌گرداند، در غیر این صورت 0.

## مراجع

* تعریف‌نوع [HeaderFunc](../../headerfunc/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [TransferCodingHeaderValue](../)
* فضای‌نام [System::Net::Http::Headers](../../)
* کتابخانه [Aspose.Slides](../../../)