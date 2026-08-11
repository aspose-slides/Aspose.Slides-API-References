---
title: IsBypassed()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار را برمی‌گرداند که نشان می‌دهد آیا برای میزبان مشخص‌شده باید از پروکسی استفاده نشود.
type: docs
weight: 40
url: /fa/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) متد


مقداری را برمی‌گرداند که نشان می‌دهد آیا باید برای میزبان مشخص‌شده از پروکسی استفاده نشود.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI میزبان برای بررسی. |

### مقدار بازگشت

در صورتی که سرور پروکسی نباید استفاده شود، True و در غیر این صورت false.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Uri](../../../system/uri/)
* کلاس [IWebProxy](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)