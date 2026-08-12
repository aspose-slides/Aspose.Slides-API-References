---
title: operator=()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: ทำการมอบหมายแบบย้ายวัตถุ SmartPtr. x จะไม่สามารถใช้งานได้.
type: docs
weight: 27
url: /th/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_\&&) เมธอด

ทำการมอบหมายแบบย้ายวัตถุ [SmartPtr](../). x จะไม่สามารถใช้ได้.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | พอยน์เตอร์สำหรับการมอบหมายแบบย้าย. |

### ค่าที่ส่งคืน

อ้างอิงถึงวัตถุนี้.

## SmartPtr::operator=(const SmartPtr_\&) เมธอด

ทำการคัดลอกมอบหมายวัตถุ [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | พอยน์เตอร์สำหรับการคัดลอกมอบหมาย. |

### ค่าที่ส่งคืน

อ้างอิงถึงวัตถุนี้.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) เมธอด

ทำการคัดลอกมอบหมายวัตถุ [SmartPtr](../). ทำการแปลงประเภทที่จำเป็น.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทของวัตถุที่ x ชี้ไป. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | พอยน์เตอร์สำหรับการคัดลอกมอบหมาย. |

### ค่าที่ส่งคืน

อ้างอิงถึงวัตถุนี้.

## SmartPtr::operator=(Pointee_ *) เมธอด

ทำการมอบหมายพอยน์เตอร์ดิบให้กับวัตถุ [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | ค่าพอยน์เตอร์ที่จะมอบหมาย. |

### ค่าที่ส่งคืน

อ้างอิงถึงวัตถุนี้.

## SmartPtr::operator=(std::nullptr_t) เมธอด

ตั้งค่าพอยน์เตอร์เป็น nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### ค่าที่ส่งคืน

อ้างอิงถึงวัตถุนี้.

## ดูเพิ่มเติม

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* คลาส [SmartPtr](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)