---
title: AreEqualContainer()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เปรียบเทียบความเท่าเทียมของสองคอนเทนเนอร์โดยใช้ตัวดำเนินการ == กับแต่ละองค์ประกอบ ทำงานกับองค์ประกอบที่ไม่ใช่ SmartPtr
type: docs
weight: 1
url: /th/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function

เปรียบเทียบความเท่ากันของสองคอนเทนเนอร์โดยใช้ตัวดำเนินการ == กับแต่ละองค์ประกอบ ทำงานกับองค์ประกอบที่ไม่ใช่ SmartPtr

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T1 | ชนิดของคอนเทนเนอร์ฝั่งซ้าย |
| T2 | ชนิดของคอนเทนเนอร์ฝั่งขวา |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | คอนเทนเนอร์ฝั่งซ้าย |
| rhs | const T2\& | คอนเทนเนอร์ฝั่งขวา |

### ค่าที่คืน

คืนค่า true หากองค์ประกอบและขนาดตรงกัน, มิฉะนั้นคืนค่า false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function

เปรียบเทียบความเท่ากันของสองคอนเทนเนอร์โดยใช้ [System::Object::Equals](../../system/object/equals/) กับแต่ละองค์ประกอบ ทำงานกับองค์ประกอบ [SmartPtr](../../system/smartptr/)

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T1 | ชนิดของคอนเทนเนอร์ฝั่งซ้าย |
| T2 | ชนิดของคอนเทนเนอร์ฝั่งขวา |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | การอ้างอิงคอนเทนเนอร์ฝั่งซ้าย |
| rhs | const T2\& | การอ้างอิงคอนเทนเนอร์ฝั่งขวา |

### ค่าที่คืน

คืนค่า true หากองค์ประกอบและขนาดตรงกัน, มิฉะนั้นคืนค่า false.

## See Also

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)