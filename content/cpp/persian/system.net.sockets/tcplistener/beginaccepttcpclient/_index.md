---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides برای مرجع API C++
description: یک عملیات پذیرش غیرهمزمان را آغاز می‌کند.
type: docs
weight: 170
url: /fa/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات پذیرش غیرهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک callback که هنگام تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر برای شناسایی منحصر به فرد هر عملیات اتصال غیرهمزمان. |

### مقدار بازگشت

یک [IAsyncResult](../../../system/iasyncresult/) شیء که نمایانگر عملیات پذیرش غیرهمزمان آغاز شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [TcpListener](../)
* فضای نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)