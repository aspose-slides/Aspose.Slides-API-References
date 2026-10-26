---
title: EndRead()
second_title: مرجع API Aspose.Slides برای C++
description: تا زمان تکمیل عملیات خواندن ناهمزمان مشخص‌شده صبر می‌کند.
type: docs
weight: 430
url: /fa/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) متد

Waits until the specified asynchronous read operation completes.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که یک عملیات خواندن ناهمزمان را نمایندگی می‌کند |

### مقدار بازگشت

تعداد بایت‌های خوانده شده در طول عملیات خواندن که توسط **asyncResult** نمایندگی می‌شود

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [SslStream](../)
* فضای‌نام [System::Net::Security](../../)
* کتابخانه [Aspose.Slides](../../../)