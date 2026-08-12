---
title: ToTiff()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: แปลงงานนำเสนออินพุตเป็นชุดของรูปภาพในรูปแบบ TIFF หากระบุชื่อไฟล์เอาต์พุตเป็น \"myPath/myFilename.tiff\" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ \"myPath/myFilename_N.tiff\" โดยที่ N คือหมายเลขสไลด์
type: docs
weight: 66
url: /th/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) เมธอด

แปลงงานนำเสนออินพุตเป็นชุดของรูปภาพในรูปแบบ TIFF  

หากระบุชื่อไฟล์เอาต์พุตเป็น "myPath/myFilename.tiff" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.tiff" โดยที่ N คือหมายเลขสไลด์

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | The input presentation. |
| outputFileName | [System::String](../../../system/string/) | The output file name. |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) เมธอด

แปลงงานนำเสนออินพุตเป็นรูปแบบ TIFF dengan ตัวเลือกที่กำหนดเอง. หากระบุชื่อไฟล์เอาต์พุตเป็น "myPath/myFilename.tiff" และ *multipage* เป็น **false** ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.tiff" โดยที่ N คือหมายเลขสไลด์ มิฉะนั้น หาก *multipage* เป็น **true** ผลลัพธ์จะเป็นเอกสารแบบหลายหน้า "myPath/myFilename.tiff".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | The input presentation. |
| outputFileName | [System::String](../../../system/string/) | The output file name. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | The TIFF saving options. |
| multipage | **bool** | Specifies whether the generated TIFF document should be a multi-page. |

## หมายเหตุ

```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [String](../../../system/string/)
* คลาส [Convert](../)
* คลาส [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)