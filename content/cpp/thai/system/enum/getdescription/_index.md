---
title: GetDescription()
second_title: เอกสารอ้างอิง API Aspose.Slides สำหรับ C++
description: ส่งคืนชื่อของค่าคงที่ enumeration ที่มีค่าตรงตามที่ระบุ
type: docs
weight: 53
url: /th/system/enum/getdescription/
---
## Enum::GetDescription(T) เมธอด

ส่งคืนชื่อของค่าคงที่ enumeration ที่มีค่าตรงตามที่ระบุ

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | T | ค่าของค่าคงที่ enum ที่ต้องการให้ส่งคืนชื่อ |

### ค่าที่ส่งคืน

ชื่อของค่าคงที่ enum ที่ระบุ

## ดูเพิ่มเติม

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)