---
title: Func()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คอนสตรัคเตอร์เริ่มต้นที่สร้าง null-Func.
type: docs
weight: 1
url: /th/system/func/func/
---
## Func::Func() คอนสตรัคเตอร์

คอนสตรัคเตอร์เริ่มต้นที่สร้าง null-Func.

```cpp
System::Func<Args>::Func()
```
## Func::Func(T\&&) คอนสตรัคเตอร์

คอนสตรัคเตอร์ที่สร้างวัตถุ [Func](../) และกำหนดค่า (ไม่ว่าจะเป็น callback จริงหรือ nullptr) ให้กับมัน.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอาร์กิวเมนต์. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arg | T\&& | อาร์กิวเมนต์. |

## Func::Func(const Func\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์คัดลอก.

```cpp
System::Func<Args>::Func(const Func &func)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) เพื่อคัดลอกข้อมูลจาก. |

## Func::Func(Func\&&) คอนสตรัคเตอร์

คอนสตรัคเตอร์ย้าย.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) เพื่อย้ายข้อมูลจาก. |

## ดูเพิ่มเติม

* คลาส [Func](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)