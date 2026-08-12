---
title: AreEqualData()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เปรียบเทียบเท่ากันของสองคอนเทนเนอร์โดยใช้ System::Object::Equals บนแต่ละองค์ประกอบ ทำงานได้กับองค์ประกอบ SmartPtr"
type: docs
weight: 14
url: /th/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function

เปรียบเทียบเท่ากันของสองคอนเทนเนอร์โดยใช้ [System::Object::Equals](../../system/object/equals/) บนแต่ละองค์ประกอบ ทำงานได้กับองค์ประกอบ [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | ประเภทคอนเทนเนอร์ด้านซ้าย. |
| T2 | ประเภทคอนเทนเนอร์ด้านขวา. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | การอ้างอิงคอนเทนเนอร์ด้านซ้าย. |
| rhs | const T2\& | การอ้างอิงคอนเทนเนอร์ด้านขวา. |

### ค่ารีเทิร์น

คืนค่า true หากองค์ประกอบและขนาดตรงกัน, false หากไม่ตรงกัน.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function

เปรียบเทียบเท่ากันของสองคอนเทนเนอร์โดยใช้ operator == บนแต่ละองค์ประกอบ ทำงานได้กับองค์ประกอบที่ไม่ใช่ SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | ประเภทคอนเทนเนอร์ด้านซ้าย. |
| T2 | ประเภทคอนเทนเนอร์ด้านขวา. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | คอนเทนเนอร์ด้านซ้าย. |
| rhs | const T2\& | คอนเทนเนอร์ด้านขวา. |

### ค่ารีเทิร์น

คืนค่า true หากองค์ประกอบและขนาดตรงกัน, false หากไม่ตรงกัน.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) function

เปรียบเทียบเท่ากันของสองคอนเทนเนอร์ที่มีชนิดเดียวกัน ทำงานได้กับองค์ประกอบที่ไม่ใช่ SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | ประเภทคอนเทนเนอร์ด้านซ้าย. |
| T2 | ประเภทคอนเทนเนอร์ด้านขวา. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T\& | คอนเทนเนอร์ด้านซ้าย. |
| rhs | const T\& | คอนเทนเนอร์ด้านขวา. |

### ค่ารีเทิร์น

คืนค่า true หากองค์ประกอบและขนาดตรงกัน, false หากไม่ตรงกัน.

## ดูเพิ่มเติม

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)