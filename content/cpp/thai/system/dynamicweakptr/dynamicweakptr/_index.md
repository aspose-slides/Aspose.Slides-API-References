---
title: DynamicWeakPtr()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างสมาร์ทพอยน์เตอร์ null.
type: docs
weight: 1
url: /th/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) คอนสตรัคเตอร์

สร้างสมาร์ทพอยน์เตอร์ null.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) คอนสตรัคเตอร์

สร้างสมาร์ทพอยน์เตอร์ที่ชี้ไปยังอ็อบเจ็กต์ที่กำหนด.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | อ็อบเจ็กต์ที่ชี้. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) คอนสตรัคเตอร์

คัดลอกสร้างสมาร์ทพอยน์เตอร์.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | สมาร์ทพอยน์เตอร์เพื่อคัดลอกข้อมูลของอ็อบเจ็กต์ที่ชี้จาก. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) คอนสตรัคเตอร์

คัดลอกสร้างสมาร์ทพอยน์เตอร์.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Template parameters

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทของอ็อบเจ็กต์ที่ชี้ของพอยน์เตอร์ต้นฉบับ. |

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | สมาร์ทพอยน์เตอร์เพื่อคัดลอกข้อมูลของอ็อบเจ็กต์ที่ชี้จาก. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) คอนสตรัคเตอร์

คัดลอกสร้างสมาร์ทพอยน์เตอร์.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | สมาร์ทพอยน์เตอร์เพื่อคัดลอกข้อมูลของอ็อบเจ็กต์ที่ชี้จาก. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) คอนสตรัคเตอร์

ย้ายสร้างสมาร์ทพอยน์เตอร์.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | สมาร์ทพอยน์เตอร์เพื่อย้ายข้อมูลของอ็อบเจ็กต์ที่ชี้จาก. จะไม่สามารถใช้ได้หลังจากเรียก. |

## See Also

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)