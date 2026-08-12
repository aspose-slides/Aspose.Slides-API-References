---
title: Add()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เพิ่มอาร์เรย์ไบต์ไปยังที่เก็บ XmlPreloadedResolver และทำแมปไปยัง URI หากที่เก็บมีการแมปสำหรับ URI เดียวกันอยู่แล้ว การแมปที่มีอยู่จะถูกทับแทน
type: docs
weight: 79
url: /th/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) เมธอด

เพิ่มอาร์เรย์ไบต์ไปยังที่เก็บ [XmlPreloadedResolver](../) และทำแผนที่ไปยัง URI หากที่เก็บมีการแมปสำหรับ URI เดียวกันอยู่แล้ว การแมปที่มีอยู่จะถูกทับแทน

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI ของข้อมูลที่กำลังถูกเพิ่มไปยังที่เก็บ [XmlPreloadedResolver](../) |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์ที่มีข้อมูลที่สอดคล้องกับ URI ที่ระบุ |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

เพิ่มอาร์เรย์ไบต์ไปยังที่เก็บ [XmlPreloadedResolver](../) และทำแผนที่ไปยัง URI หากที่เก็บมีการแมปสำหรับ URI เดียวกันอยู่แล้ว การแมปที่มีอยู่จะถูกทับแทน

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI ของข้อมูลที่กำลังถูกเพิ่มไปยังที่เก็บ [XmlPreloadedResolver](../) |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์ที่มีข้อมูลที่สอดคล้องกับ URI ที่ระบุ |
| offset | **int32_t** | ออฟเซ็ตในอาร์เรย์ไบต์ที่ให้ซึ่งตำเริ่มต้นของข้อมูล |
| count | **int32_t** | จำนวนไบต์ที่จะอ่านจากอาร์เรย์ไบต์ เริ่มจากออฟเซ็ตที่ระบุ |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) เมธอด

เพิ่มสตรีมไปยังที่เก็บ [XmlPreloadedResolver](../) และทำแผนที่ไปยัง URI หากที่เก็บมีการแมปสำหรับ URI เดียวกันอยู่แล้ว การแมปที่มีอยู่จะถูกทับแทน

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI ของข้อมูลที่กำลังถูกเพิ่มไปยังที่เก็บ [XmlPreloadedResolver](../) |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูลที่สอดคล้องกับ URI ที่ระบุ |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) เมธอด

เพิ่มสตริงที่มีข้อมูลที่โหลดล่วงหน้าไปยังที่เก็บ [XmlPreloadedResolver](../) และทำแผนที่ไปยัง URI หากที่เก็บมีการแมปสำหรับ URI เดียวกันอยู่แล้ว การแมปที่มีอยู่จะถูกทับแทน

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI ของข้อมูลที่กำลังถูกเพิ่มไปยังที่เก็บ [XmlPreloadedResolver](../) |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) ที่มีข้อมูลที่สอดคล้องกับ URI ที่ระบุ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)