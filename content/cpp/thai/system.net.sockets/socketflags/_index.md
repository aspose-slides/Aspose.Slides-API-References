---
title: SocketFlags
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ให้ค่าคงที่สำหรับข้อความของซ็อกเก็ต.
type: docs
weight: 222
url: /th/system.net.sockets/socketflags/
---
## SocketFlags enum

ให้ค่าคงที่สำหรับข้อความของซ็อกเก็ต.

```cpp
enum class SocketFlags
```

### ค่าต่าง ๆ

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | ไม่มีแฟล็กใด ๆ ที่ใช้สำหรับการเรียกนี้. |
| OutOfBand | 1 | ข้อมูล out-of-band กำลังถูกประมวลผล. |
| Peek | 2 | ดูตัวอย่างข้อความที่เข้ามา. |
| DontRoute | 4 | ส่งข้อความโดยไม่ใช้ตารางการกำหนดเส้นทาง. |
| Truncated | 256 | ข้อความมีขนาดใหญ่เกินกว่าจะใส่ในบัฟเฟอร์ที่ระบุ. ข้อความถูกตัดทอน. |
| ControlDataTruncated | 512 | ข้อมูลควบคุมมีขนาดมากกว่า 64 KB และไม่สามารถใส่ในบัฟเฟอร์ภายในได้. ข้อมูลถูกตัดทอน. |
| Broadcast | 1024 | แพ็กเกจแบบบรอดแคสต์. |
| Multicast | 2048 | แพ็กเกจแบบมัลติคาสต์. |
| Partial | 32768 | ข้อความที่ส่งหรือรับบางส่วน. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Net::Sockets](../)
* ไลบรารี [Aspose.Slides](../../)