---
title: CancellationToken
second_title: مرجع API Aspose.Slides برای C++
description: اعلام می‌کند که عملیات باید لغو شوند. این کلاس مکانیزمی برای لغو تعاونی بین رشته‌ها فراهم می‌کند که به یک رشته اجازه می‌دهد دیگران را از نیاز به لغو یک عملیات آگاه کند.
type: docs
weight: 14
url: /fa/system.threading/cancellationtoken/
---
## CancellationToken کلاس


اعلان می‌دهد که عملیات باید لغو شوند. این کلاس مکانیزمی برای لغو تعاونی بین رشته‌ها فراهم می‌کند که به یک رشته اجازه می‌دهد دیگران را از نیاز به لغو یک عملیات آگاه کند.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## متدها

| متد | توضیح |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | سازندهٔ پیش‌فرض. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | مشخص می‌کند که آیا این توکن می‌تواند در حالت لغو باشد یا نه. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | مشخص می‌کند که آیا لغو برای این توکن درخواست شده است یا نه. |
| static [CancellationToken](./) [get_None](./get_none/)() | یک مقدار خالی از نوع [System::Threading::CancellationToken](./) برمی‌گرداند. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | یک بازگشت‌خوان (callback) را ثبت می‌کند که هنگام درخواست لغو فراخوانی می‌شود. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | اگر لغو درخواست شده باشد، یک OperationCanceledException پرتاب می‌کند. |
## توضیحات



یک [CancellationToken](./) فقط می‌تواند از طریق [CancellationTokenSource](../cancellationtokensource/) مرتبط آن لغو شود. 

## موارد مرتبط

* فضای نام [System::Threading](../)
* کتابخانه [Aspose.Slides](../../)