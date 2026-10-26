---
title: operator<()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าวัตถุปัจจุบันเป็นค่าที่เป็นวันที่และเวลาที่เร็วกว่าค่าที่แทนโดยวัตถุ DateTime ที่ระบุ
type: docs
weight: 586
url: /th/system/datetime/operator_less/
---
## DateTime::operator<(DateTime) const เมธอด


กำหนดว่าวัตถุปัจจุบันเป็นค่าที่เป็นวันที่และเวลาที่เร็วกว่าค่าที่แทนโดยวัตถุ [DateTime](../) ที่ระบุ

```cpp
constexpr bool System::DateTime::operator<(DateTime other) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | [DateTime](../) | วัตถุ [DateTime](../) เพื่อเปรียบเทียบกับวัตถุปัจจุบัน |

### ค่าที่คืนกลับ

จริง หากค่าที่แทนวันที่และเวลาของวัตถุปัจจุบันเร็วกว่าค่าที่แทนโดย **other**, มิฉะนั้น - เท็จ

## DateTime::operator<(std::nullptr_t) const เมธอด




```cpp
constexpr bool System::DateTime::operator<(std::nullptr_t) const
```

## ดูเพิ่มเติม

* คลาส [DateTime](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)