---
title: EndReceive()
second_title: مرجع API Aspose.Slides برای C++
description: تا زمانی که عملیات دریافت ناهمزمان مشخص‌شده تکمیل شود، صبر می‌کند.
type: docs
weight: 534
url: /fa/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) متد

تا زمانی که عملیات دریافت ناهمزمان مشخص‌شده تکمیل شود، صبر می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که نشان‌دهنده یک عملیات دریافت ناهمزمان است. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) متد

تا زمانی که عملیات دریافت ناهمزمان مشخص‌شده تکمیل شود، صبر می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که نشان‌دهنده یک عملیات دریافت ناهمزمان است. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که کد خطا در صورت شکست عملیات دریافت در آن قرار می‌گیرد. |

### مقدار بازگشت

تعداد بایت‌های دریافت‌شده.

## موارد مرتبط

* enum [SocketError](../../socketerror/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Socket](../)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)