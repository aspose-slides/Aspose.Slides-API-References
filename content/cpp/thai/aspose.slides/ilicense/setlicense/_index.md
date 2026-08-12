---
title: SetLicense()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดใบอนุญาตให้คอมโพเนนท์
type: docs
weight: 1
url: /th/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) เมธอด

กำหนดใบอนุญาตให้คอมโพเนนท์

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | สามารถเป็นชื่อไฟล์เต็มหรือสั้น หรือชื่อของทรัพยากรฝังตัว ใช้สตริงว่างเพื่อสลับไปยังโหมดประเมินผล |
## หมายเหตุ

พยายามค้นหาใบอนุญาตในตำแหน่งต่อไปนี้:

1. เส้นทางโดยตรง
2. โฟลเดอร์ของแอสเซมบลีคอมโพเนนท์
3. โฟลเดอร์ของแอสเซมบลีที่เรียกโดยไคลเอนต์
4. โฟลเดอร์ของแอสเซมบลีเริ่มต้น
5. ทรัพยากรฝังตัวในแอสเซมบลีที่เรียกโดยไคลเอนต์

**หมายเหตุ:** บน .NET Compact Framework, จะพยายามค้นหาใบอนุญาตเฉพาะในตำแหน่งต่อไปนี้:

1. เส้นทางโดยตรง
2. ทรัพยากรฝังตัวในแอสเซมบลีที่เรียกโดยไคลเอนต์

ในตัวอย่างนี้ ระบบจะพยายามค้นหาไฟล์ใบอนุญาตชื่อ MyLicense.lic ในโฟลเดอร์ที่มีคอมโพเนนท์, ในโฟลเดอร์ที่มีแอสเซมบลีที่เรียก, ในโฟลเดอร์ของแอสเซมบลีเริ่มต้นและจากนั้นในทรัพยากรฝังตัวของแอสเซมบลีที่เรียก

```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) เมธอด

กำหนดใบอนุญาตให้คอมโพเนนท์

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่บรรจุใบอนุญาต |
## หมายเหตุ

ใช้เมธอดนี้เพื่อโหลดใบอนุญาตจากสตรีม.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## ดูเพิ่มเติม

* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [ILicense](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)