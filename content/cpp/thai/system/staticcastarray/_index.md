---
title: StaticCastArray()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการแปลงประเภทของสมาชิกในอาเรย์ที่ระบุเป็นประเภทอื่น Override สำหรับกรณีที่ From เป็น SmartPtr obj.
type: docs
weight: 2978
url: /th/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function

ทำการแปลงประเภทของสมาชิกในอาเรย์ที่ระบุเป็นประเภทอื่น Override สำหรับกรณีที่ From เป็น [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| To | ประเภทที่จะทำการแปลงสมาชิกของอาเรย์ที่ระบุ |
| From | ประเภทของสมาชิกของอาเรย์ที่ต้องการทำการแปลง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | ตัวชี้แบบ Shared pointer ไปยังอาเรย์ที่มีสมาชิกที่ต้องการทำการแปลง |

### ค่าที่ส่งกลับ

ตัวชี้ไปยังอาเรย์ใหม่ที่มีสมาชิกประเภท **To** เทียบเท่ากับสมาชิกของ **from**

เลิกใช้
:   เพิ่มเพื่อความเข้ากันได้ย้อนหลัง ใช้ ExplicitCast แทน

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function

ทำการแปลงประเภทของสมาชิกในอาเรย์ที่ระบุเป็นประเภทอื่น Override สำหรับกรณีที่ From เป็น Boxable และ To เป็น [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| To | ประเภทที่จะทำการแปลงสมาชิกของอาเรย์ที่ระบุ |
| From | ประเภทของสมาชิกของอาเรย์ที่ต้องการทำการแปลง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | ตัวชี้แบบ Shared pointer ไปยังอาเรย์ที่มีสมาชิกที่ต้องการทำการแปลง |

### ค่าที่ส่งกลับ

ตัวชี้ไปยังอาเรย์ใหม่ที่มีสมาชิกประเภท **To** เทียบเท่ากับสมาชิกของ **from**

เลิกใช้
:   เพิ่มเพื่อความเข้ากันได้ย้อนหลัง ใช้ ExplicitCast แทน

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../sharedptr/)
* คลาส [Array](../array/)
* คลาส [Object](../object/)
* โครงสร้าง [IsSmartPtr](../issmartptr/)
* โครงสร้าง [IsBoxable](../isboxable/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)