---
title: EndSend()
second_title: Aspose.Slides برای C++ مرجع API
description: تا زمان تکمیل عملیات ارسال ناهمزمان مشخص‌شده صبر می‌کند.
type: docs
weight: 508
url: /fa/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) متد

تا زمان تکمیل عملیات ارسال ناهمزمان مشخص شده صبر می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر یک عملیات ارسال ناهمزمان است. |

### مقدار بازگشت

تعداد بایت‌های ارسال‌شده.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) متد

تا زمان تکمیل عملیات ارسال ناهمزمان مشخص شده صبر می‌کند.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر یک عملیات ارسال ناهمزمان است. |
| errorCode | [SocketError](../../socketerror/)\& | پارامتر خروجی که کد خطا در زمان شکست عملیات ارسال به آن اختصاص می‌یابد. |

### مقدار بازگشت

تعداد بایت‌های ارسال‌شده.

## موارد مرتبط

* شماره‌گذاری [SocketError](../../socketerror/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Socket](../)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)