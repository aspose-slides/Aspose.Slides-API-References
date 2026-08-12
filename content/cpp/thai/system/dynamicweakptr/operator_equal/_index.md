---
title: operator=()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: ทำการมอบหมายแบบย้ายให้กับตัวชี้อัจฉริยะ.
type: docs
weight: 27
url: /th/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) เมธอด

ทำการมอบหมายแบบย้ายให้กับตัวชี้อัจฉริยะ.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | ตัวชี้ค่าที่มาจากการมอบหมายแบบย้าย |

### ค่าที่ส่งกลับ

อ้างอิงตนเอง.

## DynamicWeakPtr::operator=(const SmartPtr_&) เมธอด

ทำการมอบหมายแบบคัดลอกให้กับตัวชี้อัจฉริยะ.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | ตัวชี้ค่าที่มาจากการมอบหมายแบบคัดลอก |

### ค่าที่ส่งกลับ

อ้างอิงตนเอง.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>&) เมธอด

ทำการมอบหมายแบบคัดลอกให้กับตัวชี้อัจฉริยะ.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทของ pointee แหล่งที่มา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>& | ตัวชี้ค่าที่มาจากการมอบหมายแบบคัดลอก |

### ค่าที่ส่งกลับ

อ้างอิงตนเอง.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) เมธอด

ทำการมอบหมายให้กับตัวชี้อัจฉริยะ.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | ค่าตัวชี้ |

### ค่าที่ส่งกลับ

อ้างอิงตนเอง.

## DynamicWeakPtr::operator=(std::nullptr_t) เมธอด

ตั้งค่าตัวชี้อัจฉริยะเป็น null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### ค่าที่ส่งกลับ

อ้างอิงตนเอง.

## ดูเพิ่มเติม

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)