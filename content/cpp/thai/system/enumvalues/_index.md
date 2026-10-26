---
title: EnumValues
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้ข้อมูลเมตาเกี่ยวกับค่าคงที่ของ enumeration ประเภท E.
type: docs
weight: 794
url: /th/system/enumvalues/
---
## EnumValues คลาส

Provides meta information about enumeration constants of enum type **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| E | The type of enumeration |

## เมธอด

| Method | Description |
| --- | --- |
|  [EnumValues](./enumvalues/)() | สร้างอินสแตนซ์ |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | ส่งคืนอาร์เรย์ที่มีชื่อทั้งหมดของ enumeration **E** |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | ดึงอาร์เรย์ของชื่อของค่าคงที่ใน enumeration ที่ระบุ |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | ส่งคืนประเภทพื้นฐานของ enumeration ที่ระบุ |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | ส่งคืนประเภทพื้นฐานของ enumeration ที่ระบุ |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | ส่งคืนค่าที่บรรจุของค่าคงที่ enum ที่มีชื่อที่ระบุ |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | ส่งคืนค่าที่บรรจุของค่าคงที่ enum ที่มีค่าที่ระบุ |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | ส่งคืนอาร์เรย์ที่มีค่าทั้งหมดของ enumeration **E** |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | ส่งคืนอาร์เรย์ที่มีค่าทั้งหมดของประเภท enumeration ที่ระบุ |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | ส่งคืนอ็อบเจ็กต์ที่แสดงค่าของค่าคงที่ enumeration ของประเภท enumeration ที่ระบุด้วยชื่อที่ระบุ |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | แปลงค่าจำนวนเต็มบวก 64-bit ที่ระบุเป็นสมาชิกของ enumeration |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | แปลงอ็อบเจ็กต์ที่มีค่าจำนวนเต็มที่ระบุเป็นสมาชิกของ enumeration |
| virtual  [~EnumValues](./~enumvalues/)() | ตัวทำลาย |

## ดูเพิ่มเติม

* คลาส [EnumValuesBase](../enumvaluesbase/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)