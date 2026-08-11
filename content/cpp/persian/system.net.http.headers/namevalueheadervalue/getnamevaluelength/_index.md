---
title: GetNameValueLength()
second_title: مرجع API Aspose.Slides برای C++
description: رشته‌ای که به عنوان ورودی داده شده است را از ایندکس مشخص به یک نمونه از کلاس NameValueHeaderValue تبدیل می‌کند.
type: docs
weight: 118
url: /fa/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) متد

رشتهٔ ورودی را از ایندکس مشخص به یک نمونه از کلاس [NameValueHeaderValue](../) تبدیل می‌کند.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | [String](../../../system/string/) | یک رشته برای تجزیه. |
| startIndex | **int32_t** | یک موقعیت شروع برای تجزیه. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | یک نمونه‌ای که شیء تجزیه‌شده به آن اختصاص می‌یابد. |

### مقدار برگشتی

طول زیررشتهٔ تجزیه‌شده را برمی‌گرداند، در غیر این صورت 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) متد

رشتهٔ ورودی را از ایندکس مشخص به یک نمونه از کلاس [NameValueHeaderValue](../) تبدیل می‌کند.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | [String](../../../system/string/) | یک رشته برای تجزیه. |
| startIndex | **int32_t** | یک موقعیت شروع برای تجزیه. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | یک تابع که برای ایجاد نمونه‌های جدید از کلاس [NameValueHeaderValue](../) استفاده می‌شود. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | یک نمونه‌ای که شیء تجزیه‌شده به آن اختصاص می‌یابد. |

### مقدار برگشتی

طول زیررشتهٔ تجزیه‌شده را برمی‌گرداند، در غیر این صورت 0.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)