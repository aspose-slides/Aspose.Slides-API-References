---
title: Details_WebException()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید می‌سازد.
type: docs
weight: 40
url: /fa/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | [String](../../../system/string/) | توضیح خطا. |

## Details_WebException::Details_WebException(String, Exception) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | [String](../../../system/string/) | پیام استثنا. |
| innerException | [Exception](../../../system/exception/) | استثنای داخلی. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | [String](../../../system/string/) | پیام استثنا. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | کد وضعیت. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| message | [String](../../../system/string/) | پیام استثنا. |
| innerException | [Exception](../../../system/exception/) | استثنای داخلی. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | کد وضعیت. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | پاسخی وب که با استثنای جاری مرتبط است. |

## مراجع

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Details_WebException](../)
* Class [String](../../../system/string/)
* Class [WebResponse](../../webresponse/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)