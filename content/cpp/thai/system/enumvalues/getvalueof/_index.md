---
title: GetValueOf()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งค่าที่บรรจุของค่าคงที่ enum ที่มีชื่อระบุ
type: docs
weight: 53
url: /th/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const เมธอด


ส่งค่าที่บรรจุของค่าคงที่ enum ที่มีชื่อระบุ

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | ชื่อของค่าคงที่ enum |
| ignoreCase | **bool** | ระบุว่าควรละเลยตัวพิมพ์ใหญ่/เล็กหรือไม่เมื่อแปลความหมายของชื่อค่าคงที่ enum |

### ค่าที่คืนกลับ

ค่าที่บรรจุของค่าคงที่ enum ที่มีชื่อระบุใน **str**.

## EnumValues::GetValueOf(long) const เมธอด


ส่งค่าที่บรรจุของค่าคงที่ enum ที่มีค่าระบุ

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| val | long | ค่าของค่าคงที่ enum |

### ค่าที่คืนกลับ

ค่าที่บรรจุของค่าคงที่ enum ที่มีค่าระบุใน **str**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Object](../../object/)
* คลาส [String](../../string/)
* คลาส [EnumValues](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)