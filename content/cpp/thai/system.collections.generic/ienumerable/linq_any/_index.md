---
title: LINQ_Any()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าลำดับมีองค์ประกอบใดหรือไม่.
type: docs
weight: 157
url: /th/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() เมธอด

กำหนดว่าลำดับมีองค์ประกอบใดหรือไม่

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```

### ค่าที่ส่งคืน

true หากลำดับต้นทางมีองค์ประกอบใด; มิฉะนั้น false.

## IEnumerable::LINQ_Any(std::function\<bool(T)>) เมธอด

กำหนดว่ามีองค์ประกอบใดของลำดับหรือไม่ หรือว่าเป็นไปตามเงื่อนไข

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | ฟังก์ชันเพื่อตรวจสอบแต่ละองค์ประกอบตามเงื่อนไข |

### ค่าที่ส่งคืน

true หากลำดับต้นทางมีองค์ประกอบใด; มิฉะนั้น false.

## ดูเพิ่มเติม

* คลาส [IEnumerable](../)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)