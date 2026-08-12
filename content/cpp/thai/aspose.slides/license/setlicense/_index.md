---
title: SetLicense()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้สิทธิ์การใช้งานกับคอมโพเนนต์.
type: docs
weight: 14
url: /th/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) เมธอด


ให้สิทธิ์การใช้งานกับคอมโพเนนต์

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | สามารถเป็นชื่อไฟล์เต็มหรือสั้น หรือชื่อของทรัพยากรที่ฝังอยู่ ใช้สตริงว่างเพื่อสลับเป็นโหมดประเมินผล |
## หมายเหตุ



พยายามค้นหาลิขสิทธิ์ในตำแหน่งต่อไปนี้:

1. เส้นทางที่ระบุโดยตรง

2. โฟลเดอร์ของแอสเซมบลีคอมโพเนนต์

3. โฟลเดอร์ของแอสเซมบลีที่เรียกใช้ของไคลเอนต์

4. โฟลเดอร์ของแอสเซมบลีเริ่มต้น

5. ทรัพยากรที่ฝังอยู่ในแอสเซมบลีที่เรียกใช้ของไคลเอนต์

**Note:**บน .NET Compact Framework พยายามค้นหาลิขสิทธิ์เฉพาะในตำแหน่งเหล่านี้เท่านั้น:

1. เส้นทางที่ระบุโดยตรง

2. ทรัพยากรที่ฝังอยู่ในแอสเซมบลีที่เรียกใช้ของไคลเอนต์

ในตัวอย่างนี้ ระบบจะพยายามค้นหาไฟล์ลิขสิทธิ์ชื่อ MyLicense.lic ในโฟลเดอร์ที่มีคอมโพเนนต์ โฟลเดอร์ที่มีแอสเซมบลีที่เรียกใช้ โฟลเดอร์ของแอสเซมบลีเริ่มต้น และจากทรัพยากรที่ฝังอยู่ของแอสเซมบลีที่เรียกใช้  
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) เมธอด


ให้สิทธิ์การใช้งานกับคอมโพเนนต์

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่มีลิขสิทธิ์อยู่ |
## หมายเหตุ



ใช้เมธอดนี้เพื่อโหลดลิขสิทธิ์จากสตรีม


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [License](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)