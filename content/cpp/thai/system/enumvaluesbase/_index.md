---
title: EnumValuesBase
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คลาสพื้นฐานสำหรับคลาสที่แสดงข้อมูลเมตาของชนิด enumeration.
type: docs
weight: 807
url: /th/system/enumvaluesbase/
---
## EnumValuesBase คลาส

คลาสพื้นฐานสำหรับคลาสที่แสดงข้อมูลเมตาของชนิด enumeration

```cpp
class EnumValuesBase
```

## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | ดึงอาร์เรย์ของชื่อของค่าคงที่ใน enumeration ที่ระบุ |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | ส่งคืนประเภทพื้นฐานของ enumeration ที่ระบุ |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | ส่งคืนอาร์เรย์ที่ประกอบด้วยค่าทั้งหมดของประเภท enumeration ที่ระบุ |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | ส่งคืนออบเจกต์ที่แสดงค่าของค่าคงที่ enumeration ของประเภท enumeration ที่ระบุพร้อมชื่อที่ระบุ |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | แปลงค่าจำนวนเต็มบวก 64-bit ที่ระบุเป็นสมาชิกของ enumeration |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | แปลงออบเจกต์ที่ระบุที่มีค่าจำนวนเต็มเป็นสมาชิกของ enumeration |
## See Also

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)