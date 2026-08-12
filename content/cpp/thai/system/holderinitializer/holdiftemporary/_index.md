---
title: HoldIfTemporary()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนการอ้างอิงไปยัง rvalue (const)
type: docs
weight: 14
url: /th/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) เมธอด


ส่งคืนการอ้างอิงไปยัง rvalue (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) เมธอด


ส่งคืนการอ้างอิงไปยัง rvalue (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) เมธอด


คัดลอก lvalue ที่ส่งเข้ามาไปยัง holder, จากนั้นส่งคืนการอ้างอิงของ holder.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## ดูเพิ่มเติม

* โครงสร้าง [HolderInitializer](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)