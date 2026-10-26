---
title: BeginAcceptSocket()
second_title: Aspose.Slides برای C++ مرجع API
description: یک عملیات پذیرش ناهمزمان را آغاز می‌کند.
type: docs
weight: 144
url: /fa/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) متد


یک عملیات پذیرش ناهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک کال‌بک که پس از اتمام عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتا هر عملیات اتصال ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات پذیرش ناهمزمان آغاز شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [TcpListener](../)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)