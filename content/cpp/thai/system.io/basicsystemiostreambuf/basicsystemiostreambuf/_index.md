---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: สร้างอินสแตนซ์ใหม่ของ BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /th/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Smart pointer ไปยัง stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | โหมดการห่อหุ้ม |
| locale | const std::locale\& | โลเคลของ [Stream](../../stream/) |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์สำเนา. ถูกลบ.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) คอนสตรัคเตอร์

คอนสตรัคเตอร์การย้าย.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) ที่จะถูกย้าย |

## ดูเพิ่มเติม

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BasicSystemIOStreamBuf](../)
* Class [Stream](../../stream/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)