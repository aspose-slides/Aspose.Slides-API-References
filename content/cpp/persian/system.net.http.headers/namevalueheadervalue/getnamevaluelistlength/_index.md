---
title: GetNameValueListLength()
second_title: Aspose.Slides برای C++ مرجع API
description: یک رشتهٔ ورودی را از ایندکس مشخص شده به مجموعه‌ای از نمونه‌های کلاس NameValueHeaderValue تبدیل می‌کند و طول زیررشتهٔ تجزیه‌شده را برمی‌گرداند.
type: docs
weight: 131
url: /fa/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) متد

یک رشتهٔ ورودی را از ایندکس مشخص شده به مجموعه‌ای از نمونه‌های کلاس NameValueHeaderValue تبدیل می‌کند و طول زیررشتهٔ تجزیه‌شده را برمی‌گرداند.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | [String](../../../system/string/) | رشته‌ای برای تحلیل. |
| startIndex | **int32_t** | موقعیت شروع برای تحلیل. |
| delimiter | char16_t | رشته‌ای که برای جدا کردن آیتم‌ها در رشتهٔ مشخص شده استفاده می‌شود. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | پارامتر خروجی که مجموعهٔ تجزیه‌شده در آن اختصاص می‌یابد. |

### مقدار بازگشت

طول زیررشتهٔ تجزیه‌شده.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [ObjectCollection](../../objectcollection/)
* کلاس [NameValueHeaderValue](../)
* فضای‌نام [System::Net::Http::Headers](../../)
* کتابخانه [Aspose.Slides](../../../)