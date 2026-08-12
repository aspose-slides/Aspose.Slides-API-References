---
title: SerializationInfo()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ข้อมูล RTTI.
type: docs
weight: 1
url: /th/system.runtime.serialization/serializationinfo/serializationinfo/
---
## SerializationInfo::SerializationInfo(const System::TypeInfo\&, const System::SharedPtr\<IFormatterConverter\>\&) constructor

ข้อมูล RTTI.

```cpp
System::Runtime::Serialization::SerializationInfo::SerializationInfo(const System::TypeInfo &type, const System::SharedPtr<IFormatterConverter> &converter)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | const [System::TypeInfo](../../../system/typeinfo/)\& | [System::TypeInfo](../../../system/typeinfo/) ของวัตถุที่จะทำการ serialize. |
| converter | const [System::SharedPtr](../../../system/sharedptr/)\<[IFormatterConverter](../../iformatterconverter/)\>\& | [IFormatterConverter](../../iformatterconverter/) ที่ใช้ระหว่างการทำ deserialization. |
## หมายเหตุ

สร้างอินสแตนซ์ใหม่ของคลาส [SerializationInfo](../).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [IFormatterConverter](../../iformatterconverter/)
* คลาส [SerializationInfo](../)
* เนมสเปซ [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)