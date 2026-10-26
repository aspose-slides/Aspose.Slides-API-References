---
title: ToPng()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงงานนำเสนอที่ป้อนเข้าเป็นชุดของภาพรูปแบบ PNG  หากระบุชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.png" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.png" โดยที่ N คือหมายเลขสไลด์
type: docs
weight: 53
url: /th/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) เมธอด

แปลงงานนำเสนอที่ป้อนเข้าเป็นชุดของภาพรูปแบบ PNG  

ถ้าชื่อไฟล์ผลลัพธ์ระบุเป็น \"myPath/myFilename.png\" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ \"myPath/myFilename_N.png\" โดยที่ N คือหมายเลขสไลด์

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | งานนำเสนอที่ป้อนเข้า |
| outputFileName | [System::String](../../../system/string/) | ชื่อไฟล์ผลลัพธ์ |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) เมธอด

แปลงงานนำเสนอที่ป้อนเข้าเป็นชุดของภาพรูปแบบ PNG  

ถ้าชื่อไฟล์ผลลัพธ์ระบุเป็น \"myPath/myFilename.png\" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ \"myPath/myFilename_N.png\" โดยที่ N คือหมายเลขสไลด์

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | งานนำเสนอที่ป้อนเข้า |
| outputFileName | [System::String](../../../system/string/) | ชื่อไฟล์ผลลัพธ์ |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของแต่ละรูปภาพที่สร้าง |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) เมธอด

แปลงงานนำเสนอที่ป้อนเข้าเป็นชุดของภาพรูปแบบ PNG  

ถ้าชื่อไฟล์ผลลัพธ์ระบุเป็น \"myPath/myFilename.png\" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ \"myPath/myFilename_N.png\" โดยที่ N คือหมายเลขสไลด์

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | งานนำเสนอที่ป้อนเข้า |
| outputFileName | [System::String](../../../system/string/) | ชื่อไฟล์ผลลัพธ์ |
| scale | **float** | อัตราส่วนการปรับขนาดที่ใช้กับภาพผลลัพธ์เมื่อเทียบกับขนาดสไลด์เดิม |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์ |

## หมายเหตุ

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [String](../../../system/string/)
* คลาส [Convert](../)
* คลาส [Size](../../../system.drawing/size/)
* คลาส [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)