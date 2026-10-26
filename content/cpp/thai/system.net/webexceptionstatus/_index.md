---
title: WebExceptionStatus
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แสดงรายการรหัสสถานะของคลาส WebException.
type: docs
weight: 651
url: /th/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Enumerates the status codes of the WebException class.

```cpp
enum class WebExceptionStatus
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Success | 0 | ไม่พบข้อผิดพลาด. |
| NameResolutionFailure | 1 | บริการตรวจสอบชื่อไม่สามารถแก้ไขชื่อโฮสต์ได้. |
| ConnectFailure | 2 | ไม่สามารถติดต่อจุดบริการระยะไกลที่ระดับการส่งข้อมูลได้. |
| ReceiveFailure | 3 | ไม่ได้รับการตอบสนองที่สมบูรณ์จากเซิร์ฟเวอร์ระยะไกล. |
| SendFailure | 4 | ไม่สามารถส่งคำขอที่สมบูรณ์ไปยังเซิร์ฟเวอร์ระยะไกลได้. |
| PipelineFailure | 5 | คำขอเป็นคำขอแบบ pipelined และการเชื่อมต่อถูกปิดก่อนที่การตอบสนองจะได้รับ. |
| RequestCanceled | 6 | คำขอถูกยกเลิกหรือเกิดข้อผิดพลาดที่ไม่สามารถระบุได้. |
| ProtocolError | 7 | การตอบรับที่ได้รับจากเซิร์ฟเวอร์ครบถ้วนแต่บ่งชี้ถึงข้อผิดพลาดระดับโปรโตคอล. |
| ConnectionClosed | 8 | การเชื่อมต่อถูกปิดก่อนกำหนด. |
| TrustFailure | 9 | ไม่สามารถตรวจสอบความถูกต้องของใบรับรองเซิร์ฟเวอร์ได้. |
| SecureChannelFailure | 10 | เกิดข้อผิดพลาดขณะตั้งค่าการเชื่อมต่อโดยใช้ SSL. |
| ServerProtocolViolation | 11 | การตอบรับของเซิร์ฟเวอร์ไม่เป็นการตอบรับ HTTP ที่ถูกต้อง. |
| KeepAliveFailure | 12 | การเชื่อมต่อสำหรับคำขอที่ระบุหัวข้อ 'Keep-Alive' ถูกปิดโดยไม่คาดคิด. |
| Pending | 13 | คำขอแบบอะซิงโครนัสภายในกำลังค้างอยู่. |
| Timeout | 14 | ไม่ได้รับการตอบสนองในช่วงเวลาจำกัดของคำขอ. |
| ProxyNameResolutionFailure | 15 | บริการตรวจสอบชื่อไม่สามารถแก้ไขชื่อโฮสต์พร็อกซี่ได้. |
| UnknownError | 16 | เกิดข้อยกเว้นประเภทที่ไม่ทราบค่า. |
| MessageLengthLimitExceeded | 17 | ได้รับข้อความที่เกินขีดจำกัดที่กำหนด. |
| CacheEntryNotFound | 18 | ไม่พบรายการแคชที่ระบุ. |
| RequestProhibitedByCachePolicy | 19 | คำขอไม่ได้รับอนุญาตตามนโยบายแคช. |
| RequestProhibitedByProxy | 20 | คำขอนี้ไม่ได้รับอนุญาตจากพร็อกซี่. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)