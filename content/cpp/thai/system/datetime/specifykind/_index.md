---
title: SpecifyKind()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างอ็อบเจกต์ DateTime ใหม่ที่แสดงจำนวน ticks เดียวกันกับอ็อบเจกต์ DateTime ที่ระบุและแสดงเวลาในท้องถิ่น, เวลา UTC หรือไม่มีตามที่ระบุโดยอาร์กิวเมนต์ kind.
type: docs
weight: 833
url: /th/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) เมธอด


สร้างอ็อบเจกต์ [DateTime](../) ใหม่ที่แสดงจำนวน ticks เดียวกันกับอ็อบเจกต์ [DateTime](../) ที่ระบุและแสดงเวลาในท้องถิ่น, เวลา UTC หรือไม่มีตามที่ระบุโดยอาร์กิวเมนต์ **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [DateTime](../) | อ็อบเจกต์ [DateTime](../) เพื่อคัดลอกจำนวน ticks |
| kind | [DateTimeKind](../../datetimekind/) | ระบุว่าอ็อบเจกต์ใหม่ควรแสดงเวลาในท้องถิ่น, เวลา UTC หรือไม่แสดง |

### ค่าที่ส่งคืน

อ็อบเจกต์ [DateTime](../) ใหม่ที่แสดงจำนวน ticks เดียวกันกับ **value** และค่าของ DateTimeKind ที่ระบุโดย **kind**.

## ดูเพิ่มเติม

* Enum [DateTimeKind](../../datetimekind/)
* คลาส [DateTime](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)