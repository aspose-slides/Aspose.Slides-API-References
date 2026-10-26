---
title: Presentation()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คอนสตรักเตอร์นี้สร้างการนำเสนอใหม่ตั้งแต่เริ่มต้น การนำเสนอที่สร้างขึ้นมีสไลด์เปล่าหนึ่งสไลด์.
type: docs
weight: 417
url: /th/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() คอนสตรักเตอร์


คอนสตรักเตอร์นี้สร้างการนำเสนอใหม่ตั้งแต่เริ่มต้น การนำเสนอที่สร้างขึ้นมีสไลด์เปล่าหนึ่งสไลด์

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) คอนสตรักเตอร์


คอนสตรักเตอร์นี้สร้างการนำเสนอใหม่ตั้งแต่เริ่มต้น การนำเสนอที่สร้างขึ้นมีสไลด์เปล่าหนึ่งสไลด์

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | ตัวเลือกการโหลดเพิ่มเติม. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) คอนสตรักเตอร์


คอนสตรักเตอร์นี้เป็นกลไกหลักสำหรับการอ่าน [Presentation](../) ที่มีอยู่

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุต. |
## หมายเหตุ




```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) คอนสตรักเตอร์


คอนสตรักเตอร์นี้เป็นกลไกหลักสำหรับการอ่าน [Presentation](../) ที่มีอยู่

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุต. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | ตัวเลือกการโหลดเพิ่มเติม. |

## Presentation::Presentation(System::String) คอนสตรักเตอร์


คอนสตรักเตอร์นี้รับเส้นทางไฟล์ต้นทางซึ่งเนื้อหาของ [Presentation](../) จะถูกอ่าน

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ไฟล์อินพุต. |
## หมายเหตุ




```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) คอนสตรักเตอร์


คอนสตรักเตอร์นี้รับเส้นทางไฟล์ต้นทางซึ่งเนื้อหาของ [Presentation](../) จะถูกอ่าน

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ไฟล์อินพุต. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | ตัวเลือกการโหลดเพิ่มเติม. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Presentation](../)
* คลาส [LoadOptions](../../loadoptions/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)