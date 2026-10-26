---
title: Exchange()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แลกเปลี่ยนค่าบนตัวแปร: เก็บค่าที่ใหม่และคืนค่าที่ตัวแปรเคยมีอยู่ก่อนที่จะเก็บค่า."
type: docs
weight: 66
url: /th/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) เมธอด

แลกเปลี่ยนค่าบนตัวแปร: เก็บค่าที่ใหม่และคืนค่าที่ตัวแปรเคยมีอยู่ก่อนที่จะเก็บค่า.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ประเภทของตัวแปร. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | อ้างอิงตัวแปรเพื่อเปลี่ยนแปลง. |
| value | T | ค่าที่จะเก็บ. |

### ค่าที่คืนกลับ

ค่าของตัวแปรก่อนที่มันจะถูกเปลี่ยนแปลง.

## Interlocked::Exchange(T\&, T) เมธอด

แลกเปลี่ยนค่าบนตัวแปร: เก็บค่าที่ใหม่และคืนค่าที่ตัวแปรเคยมีอยู่ก่อนที่จะเก็บค่า. ยังไม่ได้ดำเนินการ.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ประเภทของตัวแปร. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | อ้างอิงตัวแปรเพื่อเปลี่ยนแปลง. |
| value | T | ค่าที่จะเก็บ. |

### ค่าที่คืนกลับ

ค่าของตัวแปรก่อนที่มันจะถูกเปลี่ยนแปลง.

## ดูเพิ่มเติม

* คลาส [Interlocked](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)