---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างอินสแตนซ์ใหม่ของ BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /th/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | พอยน์เตอร์ไปยังสตรีม |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | โหมดการห่อหุ้ม |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์คัดลอก. ถูกลบ.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) คอนสตรัคเตอร์

คอนสตรัคเตอร์การย้าย.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) เพื่อย้าย |

## ดูเพิ่มเติม

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../stream/)
* คลาส [BasicSystemIStreamWrapper](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)