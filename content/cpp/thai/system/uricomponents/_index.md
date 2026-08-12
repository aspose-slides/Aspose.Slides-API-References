---
title: UriComponents
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงส่วนประกอบของ URI.
type: docs
weight: 3251
url: /th/system/uricomponents/
---
## UriComponents enum

แสดงส่วนประกอบของ URI.

```cpp
enum class UriComponents
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Scheme | 1 | The Scheme data. |
| UserInfo | 2 | The UserInfo data. |
| Host | 4 | The Host data. |
| Port | 8 | The Port data. |
| SchemeAndServer | n/a | The Scheme, Host and Port data. |
| Path | 16 | The LocalPath data. |
| Query | 32 | The Query data. |
| PathAndQuery | n/a | The LocalPath and Query data. |
| HttpRequestUrl | n/a | The Scheme, Host, Port, Query and LocalPath data. |
| Fragment | 64 | The Fragment data. |
| AbsoluteUri | n/a | The Scheme, Host, Port, Quer, LocalPath and Fragment data. |
| StrongPort | 128 | ข้อมูล Port; หากข้อมูล port ไม่ปรากฏใน [Uri](../uri/) และพอร์ตเริ่มต้นได้ถูกกำหนดให้กับ Scheme, พอร์ตเริ่มต้นจะถูกส่งคืน; หากไม่มีพอร์ตเริ่มต้น, จะส่งคืน -1 |
| HostAndPort | n/a | ข้อมูล Host และ Port; หากข้อมูล port ไม่ปรากฏใน [Uri](../uri/) และพอร์ตเริ่มต้นได้ถูกกำหนดให้กับ Scheme, พอร์ตเริ่มต้นจะถูกส่งคืน. หากไม่มีพอร์ตเริ่มต้น, จะส่งคืน -1 |
| StrongAuthority | n/a | ข้อมูล UserInfo, Host, และ Port. หากไม่มีข้อมูล port ใน [Uri](../uri/) และพอร์ตเริ่มต้นได้ถูกกำหนดให้กับ Scheme, พอร์ตเริ่มต้นจะถูกส่งคืน. หากไม่มีพอร์ตเริ่มต้น, จะส่งคืน -1 |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | ระบุว่าตัวคั่นควรรวมอยู่ด้วย |
| SerializationInfoString | n/a | บริบท [Uri](../uri/) ทั้งหมดที่จำเป็นสำหรับ Serializers [Uri](../uri/). บริบทนี้รวม IPv6 scope |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)