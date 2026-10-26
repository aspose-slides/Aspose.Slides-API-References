---
title: RegisterPrefix()
second_title: مرجع API Aspose.Slides برای C++
description: کلاس فرزند WebRequest را برای URI مشخص شده ثبت می‌کند.
type: docs
weight: 92
url: /fa/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) متد


[WebRequest](../) descendant برای URI مشخص شده را ثبت می‌کند.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI یا پیشوند URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | نمونه‌های جدیدی از کلاس [WebRequest](../) ایجاد می‌کند. |

### مقدار بازگشت

در صورتی که [WebRequest](../) برای URI مشخص شده به‌طور موفقیت‌آمیز ثبت شود true و در غیر این صورت false.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [IWebRequestCreate](../../iwebrequestcreate/)
* کلاس [WebRequest](../)
* فضای‌نام [System::Net](../../)
* Library [Aspose.Slides](../../../)