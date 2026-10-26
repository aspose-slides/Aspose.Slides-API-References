---
title: AddFromPdf()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างสไลด์จากเอกสาร PDF และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชัน.
type: docs
weight: 131
url: /th/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) เมธอด

สร้างสไลด์จากเอกสาร PDF และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชัน.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | พาธไปยังเอกสาร PDF |

### ค่าที่คืนค่า

สไลด์ที่เพิ่ม
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) เมธอด


สร้างสไลด์จากเอกสาร PDF และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันโดยพิจารณาตัวเลือกการนำเข้า PDF.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | พาธไปยังเอกสาร PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | ตัวเลือกสำหรับการนำเข้า PDF |

### ค่าที่คืนค่า

สไลด์ที่เพิ่ม
## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) เมธอด


สร้างสไลด์จากเอกสาร PDF และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชัน.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่จะใช้เป็นแหล่งที่มาของเอกสาร PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | ตัวเลือกสำหรับการนำเข้า PDF |

### ค่าที่คืนค่า

สไลด์ที่เพิ่ม
## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// ตั้งค่าการตรวจจับตาราง
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) เมธอด


สร้างสไลด์จากเอกสาร PDF และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชัน.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่จะใช้เป็นแหล่งที่มาของเอกสาร PDF |

### ค่าที่คืนค่า

สไลด์ที่เพิ่ม
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ดูเพิ่มเติม

* กำหนดประเภท [ArrayPtr](../../../system/arrayptr/)
* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlide](../../islide/)
* คลาส [String](../../../system/string/)
* คลาส [ISlideCollection](../)
* คลาส [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)