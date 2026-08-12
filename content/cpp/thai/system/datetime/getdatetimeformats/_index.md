---
title: GetDateTimeFormats()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนอาร์เรย์ของสตริงที่แต่ละองค์ประกอบเป็นการแสดงผลเป็นสตริงของอ็อบเจกต์ปัจจุบันที่จัดรูปแบบด้วยหนึ่งในรูปแบบวันที่และเวลามาตรฐาน
type: docs
weight: 547
url: /th/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const เมธอด


ส่งคืนอาร์เรย์ของสตริงที่แต่ละองค์ประกอบเป็นการแสดงผลเป็นสตริงของอ็อบเจกต์ปัจจุบันที่จัดรูปแบบด้วยหนึ่งในรูปแบบวันที่และเวลามาตรฐาน

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const เมธอด


ส่งคืนอาร์เรย์ของสตริงที่แต่ละองค์ประกอบเป็นการแสดงผลเป็นสตริงของอ็อบเจกต์ปัจจุบันที่จัดรูปแบบด้วยรูปแบบวันที่และเวลามาตรฐานที่ระบุ

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | char_t | รูปแบบวันที่และเวลามาตรฐานที่ระบุ |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const เมธอด


ส่งคืนอาร์เรย์ของสตริงที่แต่ละองค์ประกอบเป็นการแสดงผลเป็นสตริงของอ็อบเจกต์ปัจจุบันที่จัดรูปแบบด้วยหนึ่งในรูปแบบวันที่และเวลามาตรฐานพร้อมผู้ให้บริการรูปแบบที่ระบุ

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้บริการรูปแบบ |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const เมธอด


ส่งคืนอาร์เรย์ของสตริงที่แต่ละองค์ประกอบเป็นการแสดงผลเป็นสตริงของอ็อบเจกต์ปัจจุบันที่จัดรูปแบบด้วยรูปแบบวันที่และเวลามาตรฐานที่ระบุและผู้ให้บริการรูปแบบ

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | char_t | รูปแบบวันที่และเวลามาตรฐานที่ระบุ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้บริการรูปแบบ |

## ดูเพิ่มเติม

* การกำหนดประเภท [ArrayPtr](../../arrayptr/)
* การกำหนดประเภท [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [DateTime](../)
* คลาส [IFormatProvider](../../iformatprovider/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)