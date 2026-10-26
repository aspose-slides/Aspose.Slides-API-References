---
title: BeginGetHostEntry()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات ناهمزمان را برای ایجاد یک نمونه جدید از کلاس IPHostEntry با استفاده از رشتهٔ مشخص‌شده‌ای که شامل نام میزبان یا آدرس IP است، آغاز می‌کند.
type: docs
weight: 105
url: /fa/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات ناهمزمان را برای ایجاد یک نمونه جدید از IPHostEntry-class با استفاده از رشتهٔ مشخص‌شده که شامل نام میزبان یا آدرس IP است، آغاز می‌کند.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | رشته‌ای که شامل نام میزبان یا آدرس IP است. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک Callback که هنگام اتمام عملیات فراخوانی می‌شود. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | دادهٔ تأمین‌شده توسط کاربر برای شناسایی یکتا هر عملیات ناهمزمان. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات ناهمزمان آغاز شده است.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات ناهمزمان را برای ایجاد یک نمونه جدید از IPHostEntry-class با استفاده از آدرس IP مشخص‌شده آغاز می‌کند.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | آدرس IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک Callback که هنگام اتمام عملیات فراخوانی می‌شود. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | دادهٔ تأمین‌شده توسط کاربر برای شناسایی یکتا هر عملیات ناهمزمان. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات ناهمزمان آغاز شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [String](../../../system/string/)
* کلاس [Object](../../../system/object/)
* کلاس [Dns](../)
* کلاس [IPAddress](../../ipaddress/)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)