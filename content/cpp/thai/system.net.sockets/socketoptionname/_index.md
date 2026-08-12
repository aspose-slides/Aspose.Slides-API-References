---
title: SocketOptionName
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดชื่อออปชันของซ็อกเก็ตสำหรับคลาส Socket.
type: docs
weight: 248
url: /th/system.net.sockets/socketoptionname/
---
## SocketOptionName enum

กำหนดชื่อออปชันของซ็อกเก็ตสำหรับคลาส [Socket](../socket/).

```cpp
enum class SocketOptionName
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Debug | 1 | บันทึกข้อมูลการดีบัก. |
| AcceptConnection | 2 | ระบุว่าซ็อกเก็ตกำลังรอการเชื่อมต่อขาเข้า. |
| ReuseAddress | 4 | ระบุว่าซ็อกเก็ตสามารถผูกกับที่อยู่ที่กำลังใช้งานอยู่ได้หรือไม่. |
| KeepAlive | 8 | เปิดใช้งานแพ็กเก็ต 'Keep-Alive' สำหรับการเชื่อมต่อซ็อกเก็ต. |
| DontRoute | 16 | ระบุว่าแพ็กเก็ตถูกส่งโดยตรงไปยังที่อยู่ของอินเทอร์เฟสหรือไม่. |
| Broadcast | 32 | ระบุว่าซ็อกเก็ตสามารถส่งข้อความบรอดแคสได้หรือไม่. |
| UseLoopback | 64 | ข้ามฮาร์ดแวร์เมื่อเป็นไปได้. |
| Linger | 128 | ระบบจะบล็อกกระบวนการขณะปิดจนกว่าจะส่งข้อมูลได้. |
| OutOfBandInline | 256 | รับข้อมูล out-of-band ในสตรีมข้อมูลปกติ. |
| DontLinger | n/a | ระบุว่าซ็อกเก็ตจะถูกปิดโดยไม่ค้างหรือไม่. |
| ExclusiveAddressUse | n/a | ซ็อกเก็ตจะใช้ที่อยู่ที่ผูกไว้อย่างเฉพาะเจาะจง. |
| SendBuffer | 4097 | ระบุขนาดบัฟเฟอร์การส่ง. |
| ReceiveBuffer | 4098 | ระบุขนาดบัฟเฟอร์การรับ. |
| SendLowWater | 4099 | ระบุปริมาณข้อมูลขั้นต่ำสำหรับการส่ง. |
| ReceiveLowWater | 4100 | ระบุปริมาณข้อมูลขั้นต่ำสำหรับการรับ. |
| SendTimeout | 4101 | ระบุเวลาหมดสำหรับการส่งแบบ synchronous. |
| ReceiveTimeout | 4102 | ระบุเวลาหมดสำหรับการรับแบบ synchronous. |
| Error | 4103 | คืนสถานะข้อผิดพลาดและเคลียร์. |
| Type | 4104 | คืนประเภทของซ็อกเก็ต. |
| ReuseUnicastPort | 12295 | ระบุว่าระบบควรเลื่อนการจัดสรรพอร์ตชั่วคราวสำหรับการเชื่อมต่อขาออกหรือไม่. |
| MaxConnections | 2147483647 | ตัวเลือกนี้ไม่ได้รับการสนับสนุน ใช้เพื่อระบุความยาวคิวสูงสุดสำหรับการฟัง. |
| IPOptions | 1 | ระบุออปชัน IP ที่ต้องแทรกลงในแพ็กเก็ตส่งออก. |
| HeaderIncluded | 2 | ส่วนหัวถูกรวมในแพ็กเก็ตส่งออก. |
| TypeOfService | 3 | เปลี่ยนประเภทของฟิลด์บริการในส่วนหัว IP. |
| IpTimeToLive | 4 | ค่า time to live ของ IP. |
| MulticastInterface | 9 | ตั้งค่าอินเทอร์เฟสสำหรับแพ็กเก็ตมัลติแคสต์ขาออก. |
| MulticastTimeToLive | 10 | ค่า time to live ของ IP multicast. |
| MulticastLoopback | 11 | การทำ loopback ของ IP Multicast. |
| AddMembership | 12 | เพิ่มการเป็นสมาชิกกลุ่ม IP. |
| DropMembership | 13 | ลบการเป็นสมาชิกกลุ่ม IP. |
| DontFragment | 14 | ห้ามทำ fragmentation แพ็กเก็ต IP. |
| AddSourceMembership | 15 | เข้าร่วมกลุ่ม/แหล่ง IP. |
| DropSourceMembership | 16 | ออกจากกลุ่ม/แหล่ง IP. |
| BlockSource | 17 | บล็อกกลุ่ม/แหล่ง IP. |
| UnblockSource | 18 | ปลดบล็อกกลุ่ม/แหล่ง IP. |
| PacketInformation | 19 | รับข้อมูลแพ็กเก็ตสำหรับ IPv4. |
| HopLimit | 21 | ส่งค่าเต็มจำนวนที่บรรจุจำนวน HOP ของแพ็กเก็ต. |
| IPProtectionLevel | 23 | เปิดการจำกัดซ็อกเก็ต IPv6 ให้อยู่ในขอบเขตที่ระบุ. |
| IPv6Only | 27 | ซ็อกเก็ตจำกัดให้ส่งและรับแพ็กเก็ต IPv6 เท่านั้น. |
| NoDelay | 1 | ปิดการทำงานของอัลกอริทึม Nagle สำหรับการรวมแพ็กเก็ตส่ง. |
| BsdUrgent | 2 | ใช้ข้อมูลเร่งด่วนตามที่กำหนดใน RFC-1222. |
| Expedited | 2 | ใช้ข้อมูลเร่งด่วนตามที่กำหนดใน RFC-1222. |
| NoChecksum | 1 | ส่งแพ็กเก็ต UDP ที่ checksum ตั้งเป็นศูนย์. |
| ChecksumCoverage | 20 | ตั้งหรือรับค่า coverage ของ UDP checksum. |
| UpdateAcceptContext | 28683 | อัปเดตซ็อกเก็ตคลายเอนท์ให้มีคุณสมบัติเช่นเดียวกับซ็อกเก็ตที่กำลังฟัง. |
| UpdateConnectContext | 28688 | อัปเดตซ็อกเก็ตคลายเอนท์ให้มีคุณสมบัติเช่นเดียวกับซ็อกเก็ตที่กำลังฟัง. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Net::Sockets](../)
* ไลบรารี [Aspose.Slides](../../)