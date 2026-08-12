---
title: ToObject()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: แปลงค่าจำนวนเต็มบวกขนาด 64-bit ที่ระบุเป็นสมาชิกของ enumeration
type: docs
weight: 40
url: /th/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) เมธอด


แปลงค่าเลขเต็มบวกขนาด 64-bit ที่ระบุเป็นสมาชิกของ enumeration

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | ประเภท enumeration ที่จะคืนค่า |
| value | **uint64_t** | ค่าที่จะแปลงเป็นสมาชิกของ enumeration |

### Return Value

อินสแตนซ์ของ enumeration ที่ตั้งค่าเป็นค่า

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) เมธอด


แปลงอ็อบเจ็กต์ที่ระบุพร้อมค่าจำนวนเต็มเป็นสมาชิกของ enumeration

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | ประเภท enumeration ที่จะคืนค่า |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | ค่าที่จะแปลงเป็นสมาชิกของ enumeration |

### Return Value

อ็อบเจ็กต์ enumeration ที่ค่าของมันคือ value

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Object](../../object/)
* คลาส [TypeInfo](../../typeinfo/)
* คลาส [EnumValuesBase](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)