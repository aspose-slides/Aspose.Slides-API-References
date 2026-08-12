---
title: GetName()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: คืนชื่อของค่าคงที่ของ enumeration ที่มีค่าตามที่ระบุ
type: docs
weight: 40
url: /th/system/enum/getname/
---
## Enum::GetName(T) เมธอด


Returns the name of the enumeration constant that has the specified value.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | T | ค่าของ enum constant ที่ต้องการคืนชื่อ |

### ค่าที่คืนกลับ

ชื่อของ enum constant ที่ระบุ

## ดูเพิ่มเติม

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)