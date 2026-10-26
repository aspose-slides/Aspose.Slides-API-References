---
title: OdpException
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แทนประเภทข้อยกเว้นภายในมาตรฐาน
type: docs
url: /th/com.aspose.slides/odpexception/
---
**การสืบทอด:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

แทนประเภทข้อยกเว้นภายในมาตรฐาน
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [OdpException()](#OdpException--) | Default constructor |
| [OdpException(String message)](#OdpException-java.lang.String-) | Constructor allowing a message to be added to this exception. |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | Constructor for an exception containing a message and an embedded exception. |
### OdpException() {#OdpException--}
```
public OdpException()
```

คอนสตรัคเตอร์เริ่มต้น

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```

คอนสตรัคเตอร์ที่อนุญาตให้เพิ่มข้อความไปยังข้อยกเว้นนี้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | message |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```

คอนสตรัคเตอร์สำหรับข้อยกเว้นที่มีข้อความและข้อยกเว้นฝังอยู่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | ข้อยกเว้นต้นฉบับ |