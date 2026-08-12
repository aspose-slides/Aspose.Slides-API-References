---
title: ToJpeg()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงงานนำเสนอที่ได้รับเป็นชุดของภาพในรูปแบบ JPEG.  หากกำหนดชื่อไฟล์ผลลัพธ์เป็น \"myPath/myFilename.jpeg\" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ \"myPath/myFilename_N.jpeg\" โดยที่ N คือหมายเลขสไลด์.
type: docs
weight: 40
url: /th/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) method

แปลงงานนำเสนอที่ได้รับเป็นชุดของรูปภาพในรูปแบบ JPEG.

หากกำหนดชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.jpeg" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.jpeg" โดยที่ N คือหมายเลขของสไลด์.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | งานนำเสนอที่ได้รับเข้ามา. |
| outputFileName | [System::String](../../../system/string/) | ชื่อไฟล์ผลลัพธ์. |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) method

แปลงงานนำเสนอที่ได้รับเป็นชุดของรูปภาพในรูปแบบ JPEG.

หากกำหนดชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.jpeg" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.jpeg" โดยที่ N คือหมายเลขของสไลด์.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | งานนำเสนอที่ได้รับเข้ามา |
| outputFileName | [System::String](../../../system/string/) | ชื่อไฟล์ผลลัพธ์. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของแต่ละภาพที่สร้างขึ้น. |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) method

แปลงงานนำเสนอที่ได้รับเป็นชุดของรูปภาพในรูปแบบ JPEG.

หากกำหนดชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.jpeg" ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.jpeg" โดยที่ N คือหมายเลขของสไลด์.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | งานนำเสนอที่ได้รับเข้ามา. |
| outputFileName | [System::String](../../../system/string/) | ชื่อไฟล์ผลลัพธ์. |
| scale | **float** | ปัจจัยสเกลที่ใช้กับภาพผลลัพธ์เมื่อเทียบกับขนาดสไลด์ต้นฉบับ. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์. |

## หมายเหตุ

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [String](../../../system/string/)
* คลาส [Convert](../)
* คลาส [Size](../../../system.drawing/size/)
* คลาส [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* เนมส페ซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)