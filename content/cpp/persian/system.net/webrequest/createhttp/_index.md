---
title: CreateHttp()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس WebRequest را با استفاده از URI مشخص‌شده ایجاد می‌کند.
type: docs
weight: 79
url: /fa/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) متد

یک نمونه جدید از کلاس [WebRequest](../) را با استفاده از URI مشخص‌شده ایجاد می‌کند.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | URI‌ای که برای ایجاد یک نمونه جدید از کلاس [WebRequest](../) استفاده می‌شود. |

### مقدار بازگشتی

یک نمونه‌ی تازه ایجاد شده از WebRequest-class.

## یادداشت‌ها

هنگامی که URI مشخص‌شده با هر طرحی غیر از [http://](http://) یا [https://](https://) شروع شود، NotSupportedException پرتاب می‌شود.

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) متد

یک نمونه جدید از کلاس [WebRequest](../) را با استفاده از URI مشخص‌شده ایجاد می‌کند.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI‌ای که برای ایجاد یک نمونه جدید از کلاس [WebRequest](../) استفاده می‌شود. |

### مقدار بازگشتی

یک نمونه‌ی تازه ایجاد شده از WebRequest-class.

## یادداشت‌ها

هنگامی که URI مشخص‌شده با هر طرحی غیر از [http://](http://) یا [https://](https://) شروع شود، NotSupportedException پرتاب می‌شود.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [HttpWebRequest](../../httpwebrequest/)
* کلاس [String](../../../system/string/)
* کلاس [WebRequest](../)
* کلاس [Uri](../../../system/uri/)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)