---
title: Equals< float, float >()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "การกำหนดพิเศษสำหรับค่าจุดลอยแบบความแม่นยำเดี่ยว แม้ว่าค่า NaN ของจุดลบสองค่าจะถูกกำหนดโดย IEC 60559:1989 ให้เปรียบเทียบเป็นไม่เท่ากันเสมอ สัญญาสำหรับ System.Object.Equals ต้องการให้การแทนที่ต้องสอดคล้องกับข้อกำหนดของตัวดำเนินการเทียบเท่า ดังนั้น System.Double.Equals และ System.Single.Equals จะคืนค่า True เมื่อเปรียบเทียบ NaN สองค่า ในขณะที่ตัวดำเนินการเท่ากับจะคืนค่า False ในกรณีนั้น ตามที่มาตรฐานกำหนด"
type: docs
weight: 2705
url: /th/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float&, const float&) ฟังก์ชัน

การกำหนดพิเศษสำหรับค่าจุดลอยแบบความแม่นยำเดี่ยว แม้ว่าค่า NaN แบบจุดลบน้อยสองค่า จะถูกกำหนดโดย IEC 60559:1989 ให้เปรียบเทียบเป็นไม่เท่ากันเสมอ แต่สัญญาสำหรับ [System.Object.Equals](../object/equals/) ต้องการให้การแทนที่ต้องสอดคล้องกับข้อกำหนดของตัวดำเนินการเทียบเท่า ดังนั้น System.Double.Equals และ System.Single.Equals จะคืนค่า True เมื่อตรวจเปรียบเทียบ NaN สองค่า ในขณะที่ตัวดำเนินการเท่ากับคืนค่า False ในกรณีนั้น ตามที่มาตรฐานกำหนด

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const **float**\& | ตัวเปรียบเทียบแรก |
| b | const **float**\& | ตัวเปรียบเทียบที่สอง |

### ค่าที่ส่งคืน

True ถ้าค่าทั้งสองเป็น NaN หรือเท่ากัน, หากไม่ใช่ - false

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)