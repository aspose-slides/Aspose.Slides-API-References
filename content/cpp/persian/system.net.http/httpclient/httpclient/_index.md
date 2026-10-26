---
title: HttpClient()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید می‌سازد.
type: docs
weight: 92
url: /fa/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP handler مورد استفاده برای ارسال درخواست‌ها. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP handler مورد استفاده برای ارسال درخواست‌ها. |
| disposeHandler | **bool** | مقداری که نشان می‌دهد آیا handler هنگام از بین رفتن این نمونه باید از بین رود یا خیر. |

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [HttpClient](../)
* کلاس [HttpMessageHandler](../../httpmessagehandler/)
* فضای نام [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)