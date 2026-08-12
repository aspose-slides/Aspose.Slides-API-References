---
title: GetHashCode()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ส่งคืนรหัสแฮชสำหรับค่าที่เป็นสเกลาร์ที่ระบุ
type: docs
weight: 2484
url: /th/system/gethashcode/
---
## System::GetHashCode(const T\&) ฟังก์ชัน

ส่งคืนรหัสแฮชสำหรับค่าที่เป็นสเกลาร์ที่ระบุ

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของค่าที่ฟังก์ชันสร้างรหัสแฮชให้ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | ค่าที่จะสร้างรหัสแฮชให้ |

### ค่าที่ส่งกลับ

รหัสแฮชที่สร้างสำหรับค่าที่ระบุ

## System::GetHashCode(const T\&) ฟังก์ชัน

ส่งคืนรหัสแฮชสำหรับอ็อบเจ็กต์ที่ระบุ

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์ที่ฟังก์ชันสร้างรหัสแฮชให้ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | The [SmartPtr](../smartptr/) ชี้ไปที่อ็อบเจ็กต์ที่จะสร้างรหัสแฮชให้ |

### ค่าที่ส่งกลับ

รหัสแฮชที่สร้างสำหรับอ็อบเจ็กต์ที่ระบุ

## System::GetHashCode(const T\&) ฟังก์ชัน

ส่งคืนรหัสแฮชสำหรับอ็อบเจ็กต์ที่ระบุซึ่งเป็นข้อยกเว้น

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์ที่ฟังก์ชันสร้างรหัสแฮชให้ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | ตัวห่อข้อยกเว้นที่มีอ็อบเจ็กต์ที่จะสร้างรหัสแฮชให้ |

### ค่าที่ส่งกลับ

รหัสแฮชที่สร้างสำหรับอ็อบเจ็กต์ที่ระบุ

## System::GetHashCode(const T\&) ฟังก์ชัน

ส่งคืนรหัสแฮชสำหรับอ็อบเจ็กต์ที่ระบุซึ่งไม่ใช่สมาร์ทพอยเตอร์หรือข้อยกเว้น

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์ที่ฟังก์ชันสร้างรหัสแฮชให้ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | การอ้างอิงคงที่ไปยังอ็อบเจ็กต์ที่จะสร้างรหัสแฮชให้ |

### ค่าที่ส่งกลับ

รหัสแฮชที่สร้างสำหรับอ็อบเจ็กต์ที่ระบุ

## System::GetHashCode(const std::thread::id\&) ฟังก์ชัน

การจำเพาะสำหรับ std::thread::id; ส่งคืนรหัสแฮชสำหรับอ็อบเจ็กต์เธรดที่ระบุ

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## ดูเพิ่มเติม

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* เนมสเปซ [System](../)
* Library [Aspose.Slides](../../)