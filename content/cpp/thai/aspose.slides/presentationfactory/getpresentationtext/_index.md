---
title: GetPresentationText()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงข้อความดิบจากสไลด์
type: docs
weight: 53
url: /th/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) เมธอด

ดึงข้อความดิบจากสไลด์

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Input file |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### ค่าที่คืน

อินสแตนซ์ของ [PresentationText](../../presentationtext/) ที่มีอาร์เรย์ SlideText แทนข้อความดิบของสไลด์

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) เมธอด

ดึงข้อความดิบจากสไลด์

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### ค่าที่คืน

อินสแตนซ์ของ [PresentationText](../../presentationtext/) ที่มีอาร์เรย์ SlideText แทนข้อความดิบของสไลด์

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) เมธอด

ดึงข้อความดิบจากสไลด์

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### ค่าที่คืน

อินสแตนซ์ของ [PresentationText](../../presentationtext/) ที่มีอาร์เรย์ SlideText แทนข้อความดิบของสไลด์

## ดูเพิ่มเติม

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPresentationText](../../ipresentationtext/)
* คลาส [String](../../../system/string/)
* คลาส [PresentationFactory](../)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [ILoadOptions](../../iloadoptions/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)