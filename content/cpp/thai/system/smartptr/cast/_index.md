---
title: Cast()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงตัวชี้เป็นประเภทของมันเอง.
type: docs
weight: 287
url: /th/system/smartptr/cast/
---
## SmartPtr::Cast() const เมธอด

แปลงตัวชี้เป็นประเภทของมันเอง.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Y | ประเภทเป้าหมายของวัตถุที่ชี้ |
| Check | แฟล็กเพื่อขว้างข้อยกเว้นหากไม่มีการแคสที่สามารถทำได้ |

### ค่าที่ส่งคืน

ตัวชี้ของประเภทที่เปลี่ยนแปลงซึ่งอยู่ในโหมด shared เสมอ.

## SmartPtr::Cast() const เมธอด

แปลงตัวชี้เป็นประเภทพื้นฐานโดยใช้ static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Y | ประเภทเป้าหมายของวัตถุที่ชี้ |
| Check | แฟล็กเพื่อขว้างข้อยกเว้นหากไม่มีการแคสที่สามารถทำได้ |

### ค่าที่ส่งคืน

ตัวชี้ของประเภทที่เปลี่ยนแปลงซึ่งอยู่ในโหมด shared เสมอ.

## SmartPtr::Cast() const เมธอด

แปลงตัวชี้เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Y | ประเภทเป้าหมายของวัตถุที่ชี้ |
| Check | แฟล็กเพื่อขว้างข้อยกเว้นหากไม่มีการแคสที่สามารถทำได้ |

### ค่าที่ส่งคืน

ตัวชี้ของประเภทที่เปลี่ยนแปลงซึ่งอยู่ในโหมด shared เสมอ. ขว้าง InvalidCastException หากไม่มีการแปลงที่สามารถทำได้.

## SmartPtr::Cast() const เมธอด

แปลงตัวชี้เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Y | ประเภทเป้าหมายของวัตถุที่ชี้ |
| Check | แฟล็กเพื่อขว้างข้อยกเว้นหากไม่มีการแคสที่สามารถทำได้ |

### ค่าที่ส่งคืน

ตัวชี้ของประเภทที่เปลี่ยนแปลงซึ่งอยู่ในโหมด shared เสมอ. ส่งคืน nullptr หากไม่มีการแปลงที่สามารถทำได้.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)