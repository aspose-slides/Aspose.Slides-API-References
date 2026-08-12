---
title: Details_WebException()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ใหม่.
type: docs
weight: 40
url: /th/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | [String](../../../system/string/) | คำอธิบายข้อผิดพลาด. |

## Details_WebException::Details_WebException(String, Exception) คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | [String](../../../system/string/) | ข้อความของข้อยกเว้น. |
| innerException | [Exception](../../../system/exception/) | ข้อยกเว้นภายใน. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | [String](../../../system/string/) | ข้อความของข้อยกเว้น. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | รหัสสถานะ. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | [String](../../../system/string/) | ข้อความของข้อยกเว้น. |
| innerException | [Exception](../../../system/exception/) | ข้อยกเว้นภายใน. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | รหัสสถานะ. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | การตอบสนองเว็บที่เชื่อมโยงกับข้อยกเว้นปัจจุบัน. |

## ดูเพิ่มเติม

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Details_WebException](../)
* Class [String](../../../system/string/)
* Class [WebResponse](../../webresponse/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)