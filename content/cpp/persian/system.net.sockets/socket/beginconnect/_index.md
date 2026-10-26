---
title: BeginConnect()
second_title: Aspose.Slides برای مرجع API C++
description: یک عملیات اتصال ناهمزمان را آغاز می‌کند.
type: docs
weight: 573
url: /fa/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) متد


یک عملیات اتصال ناهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطه انتهایی ریموت. |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک فراخوانی که پس از تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتای هر عملیات اتصال ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات اتصال ناهمزمان آغاز شده است.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد


یک عملیات اتصال ناهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | [String](../../../system/string/) | نام میزبان ریموت. |
| port | **int32_t** | شماره پورت میزبان ریموت. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک فراخوانی که پس از تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتای هر عملیات اتصال ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات اتصال ناهمزمان آغاز شده است.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد


یک عملیات اتصال ناهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | آدرس IP میزبان ریموت. |
| port | **int32_t** | شماره پورت میزبان ریموت. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک فراخوانی که پس از تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتای هر عملیات اتصال ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات اتصال ناهمزمان آغاز شده است.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد


یک عملیات اتصال ناهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | آدرس‌های IP میزبان ریموت. |
| port | **int32_t** | شماره پورت میزبان ریموت. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک فراخوانی که پس از تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتای هر عملیات اتصال ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات اتصال ناهمزمان آغاز شده است.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [AsyncCallback](../../../system/asynccallback/)
* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [EndPoint](../../../system.net/endpoint/)
* کلاس [Object](../../../system/object/)
* کلاس [Socket](../)
* کلاس [String](../../../system/string/)
* کلاس [IPAddress](../../../system.net/ipaddress/)
* فضای نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)