---
title: operator>>()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงสตริงจากสตรีมอินพุตโดยใช้การเข้ารหัส UTF-8.
type: docs
weight: 3004
url: /th/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) function

ดึงสตริงจากสตรีมอินพุตโดยใช้การเข้ารหัส UTF-8.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| in | std::istream\& | อ็อบเจ็กต์สตรีมอินพุต (การสร้างอินสแตนซ์ของ **basic_ostream** ด้วย **char**). |
| str | [String](../string/)\& | สตริงที่อ่านจากสตรีมอินพุต. |

### ค่าที่ส่งคืน

สตรีมอินพุตที่สตริงถูกดึงออกมา.

## System::operator>>(std::wistream\&, String\&) function

ดึงสตริงจากสตรีมอินพุต.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| in | std::wistream\& | อ็อบเจ็กต์สตรีมอินพุต (การสร้างอินสแตนซ์ของ **basic_ostream** กับ ****wchar_t****). |
| str | [String](../string/)\& | สตริงที่อ่านจากสตรีมอินพุต. |

### ค่าที่ส่งคืน

สตรีมอินพุตที่สตริงถูกดึงออกมา.

## ดูเพิ่มเติม

* คลาส [String](../string/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)