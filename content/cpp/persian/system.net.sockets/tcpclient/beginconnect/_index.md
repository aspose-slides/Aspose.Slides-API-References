---
title: BeginConnect()
second_title: Aspose.Slides برای C++ مرجع API
description: یک عملیات اتصال غیرهمزمان را آغاز می‌کند.
type: docs
weight: 261
url: /fa/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد


یک عملیات اتصال غیرهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | [String](../../../system/string/) | نام میزبان راه دور. |
| port | **int32_t** | پورت میزبان راه دور. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک فراخوانی که پس از پایان عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتا هر عملیات اتصال غیرهمزمان استفاده می‌شود. |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات اتصال غیرهمزمان آغاز شده است.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد


یک عملیات اتصال غیرهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | آدرس IP یک میزبان راه دور. |
| port | **int32_t** | پورت میزبان راه دور. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک فراخوانی که پس از پایان عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتا هر عملیات اتصال غیرهمزمان استفاده می‌شود. |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات اتصال غیرهمزمان آغاز شده است.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد


یک عملیات اتصال غیرهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | آدرس‌های IP یک میزبان راه دور. |
| port | **int32_t** | پورت میزبان راه دور. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک فراخوانی که پس از پایان عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتا هر عملیات اتصال غیرهمزمان استفاده می‌شود. |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات اتصال غیرهمزمان آغاز شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [String](../../../system/string/)
* کلاس [Object](../../../system/object/)
* کلاس [TcpClient](../)
* کلاس [IPAddress](../../../system.net/ipaddress/)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)