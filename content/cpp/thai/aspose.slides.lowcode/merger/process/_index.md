---
title: Process()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รวมไฟล์งานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์งานนำเสนอเดียว
type: docs
weight: 1
url: /th/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) เมธอด

รวมไฟล์งานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์งานนำเสนอเดียว

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | อาร์เรย์ของชื่อไฟล์การนำเสนอที่เป็นอินพุต |
| outputFileName | [System::String](../../../system/string/) | ชื่อไฟล์ผลลัพธ์ของไฟล์การนำเสนอที่รวมแล้ว |
## หมายเหตุ

```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) เมธอด

รวมไฟล์งานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์งานนำเสนอเดียว

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | อาร์เรย์ของชื่อไฟล์การนำเสนอที่เป็นอินพุต |
| outputFileName | [System::String](../../../system/string/) | ชื่อไฟล์ผลลัพธ์ของไฟล์การนำเสนอที่รวมแล้ว |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | ตัวเลือกเพิ่มเติมที่กำหนดวิธีการบันทึกการนำเสนอที่รวม |
## หมายเหตุ

```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) เมธอด

รวมไฟล์งานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์งานนำเสนอเดียว

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | อาร์เรย์ของชื่อไฟล์การนำเสนอที่เป็นอินพุต |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมเอาต์พุต |
## หมายเหตุ

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) เมธอด

รวมไฟล์งานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์งานนำเสนอเดียว

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | อาร์เรย์ของชื่อไฟล์การนำเสนอที่เป็นอินพุต |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมเอาต์พุต |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | ตัวเลือกเพิ่มเติมที่กำหนดวิธีการบันทึกการนำเสนอที่รวม |
## หมายเหตุ

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Merger](../)
* คลาส [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปส [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)