---
title: AreFPNaN()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: รายละเอียดเนมสเปซ
type: docs
weight: 1
url: /th/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) ฟังก์ชัน

เนมสเปซ [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### ค่าที่คืน

True if both **lhs** and **rhs** are floating point values, false otherwise.

## ข้อคิดเห็น

Checks that two floating point values are both NaNs. Handles situation when non-signalling NaN is supported. 

## System::TestPredicates::AreFPNaN(T1, T2) ฟังก์ชัน

Checks that two floating point values are both NaNs. Handles situation when non-signalling NaN is not supported.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### ค่าที่คืน

Always returns false as NaN value is not supported.

## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates](../)
* ไลบรารี [Aspose.Slides](../../)