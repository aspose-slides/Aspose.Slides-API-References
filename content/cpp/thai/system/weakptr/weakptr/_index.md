---
title: WeakPtr()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างพอยน์เตอร์เป็นค่า null.
type: docs
weight: 1
url: /th/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) คอนสตรัคเตอร์

สร้างพอยน์เตอร์เป็นค่า null.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) คอนสตรัคเตอร์

สร้าง weak pointer ไปยังอ็อบเจกต์ที่ระบุ.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) เพื่อสร้าง weak pointer ไปยัง |

## WeakPtr::WeakPtr(const SmartPtr_&) คอนสตรัคเตอร์

สร้าง weak pointer ที่อ้างอิงถึงพอยน์เตอร์เดียวกันที่ ptr ชี้ไป.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | พอยน์เตอร์เพื่อคัดลอกค่าที่ชี้จาก |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) คอนสตรัคเตอร์

สร้าง weak pointer ที่อ้างอิงถึงพอยน์เตอร์เดียวกันที่ x ชี้ไป.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทของพอยน์เตอร์ต้นทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | พอยน์เตอร์เพื่อคัดลอกค่าที่ชี้จาก |

## WeakPtr::WeakPtr(const WeakPtr_&) คอนสตรัคเตอร์

สร้าง weak pointer โดยคัดลอก.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | พอยน์เตอร์เพื่อคัดลอกค่าที่ชี้จาก |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) คอนสตรัคเตอร์

สร้าง weak pointer โดยคัดลอก.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทของพอยน์เตอร์ต้นทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | พอยน์เตอร์เพื่อคัดลอกค่าที่ชี้จาก |

## WeakPtr::WeakPtr(SmartPtr_&&) คอนสตรัคเตอร์

สร้าง weak pointer โดยย้าย.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | พอยน์เตอร์เพื่อย้ายค่าที่ชี้จาก |

## ดูเพิ่มเติม

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* คลาส [WeakPtr](../)
* คลาส [SmartPtr](../../smartptr/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)