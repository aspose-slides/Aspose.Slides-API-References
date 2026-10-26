---
title: Equals()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าพื้นที่ที่ระบุเป็นเดียวกับพื้นที่ที่อ็อบเจกต์ปัจจุบันแทนบนพื้นผิวการวาดที่ระบุ
type: docs
weight: 157
url: /th/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) เมธอด


กำหนดว่าพื้นที่ที่ระบุเป็นเดียวกับพื้นที่ที่อ็อบเจกต์ปัจจุบันแทนบนพื้นผิวการวาดที่ระบุหรือไม่

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | พื้นที่ที่จะเปรียบเทียบกับพื้นที่นี้ |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | พื้นผิวการวาด |

### ค่าที่คืนกลับ

True ถ้าภายในของพื้นที่ที่ระบุเหมือนกับภายในของพื้นที่ที่แสดงโดยอ็อบเจกต์ปัจจุบันเมื่อใช้การแปลงที่เชื่อมโยงกับพารามิเตอร์ **g**; มิฉะนั้น - false

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)