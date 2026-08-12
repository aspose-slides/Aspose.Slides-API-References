---
title: Exists()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าวัตถุ Array ที่ระบุมีองค์ประกอบที่ตรงตามข้อกำหนดของพรีดิเคตที่ระบุหรือไม่
type: docs
weight: 781
url: /th/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) เมธอด


กำหนดว่าวัตถุ [Array](../) ที่ระบุมีองค์ประกอบที่ตอบสนองตามเงื่อนไขของพรีดิเคตที่ระบุหรือไม่

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | อาร์เรย์สำหรับค้นหาองค์ประกอบ |
| match | std::function\<**bool**(T)> | ออบเจ็กต์ฟังก์ชันที่กำหนดข้อกำหนดและตรวจสอบว่าองค์ประกอบตรงตามข้อกำหนดหรือไม่ |

### ค่ารีเทิร์น

จริงถ้า **arr** มีองค์ประกอบที่ตรงตามข้อกำหนดที่กำหนดโดย **match**

## ดูเพิ่มเติม

* typedef [ArrayPtr](../../arrayptr/)
* คลาส [Array](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)