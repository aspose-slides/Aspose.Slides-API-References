---
title: GetPresentationText()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ดึงข้อความดิบจากสไลด์
type: docs
weight: 40
url: /th/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method


ดึงข้อความดิบจากสไลด์

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ไฟล์อินพุต |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | โหมดการสกัด |

### ค่าที่คืน

อินสแตนซ์ของ [PresentationText](../../presentationtext/) ที่มีอาร์เรย์ SlideText แสดงข้อความดิบของสไลด์

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method


ดึงข้อความดิบจากสไลด์

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุต |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | โหมดการสกัด |

### ค่าที่คืน

อินสแตนซ์ของ [PresentationText](../../presentationtext/) ที่มีอาร์เรย์ SlideText แสดงข้อความดิบของสไลด์

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method


ดึงข้อความดิบจากสไลด์

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุต |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | โหมดการสกัด |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ตัวเลือกการโหลด |

### ค่าที่คืน

อินสแตนซ์ของ [PresentationText](../../presentationtext/) ที่มีอาร์เรย์ SlideText แสดงข้อความดิบของสไลด์

## ดูเพิ่มเติม

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPresentationText](../../ipresentationtext/)
* คลาส [String](../../../system/string/)
* คลาส [IPresentationFactory](../)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [ILoadOptions](../../iloadoptions/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)