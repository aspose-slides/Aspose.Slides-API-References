---
title: WriteAsSvg()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: บันทึกเนื้อหาของสไลด์เป็นไฟล์ SVG.
type: docs
weight: 157
url: /th/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) เมธอด


บันทึกเนื้อหา slide เป็นไฟล์ SVG

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมเป้าหมาย |
## หมายเหตุ



ตัวอย่างโค้ดต่อไปนี้แสดงวิธีแปลงสไลด์แรกจากงานนำเสนอ PowerPoint ให้เป็นไฟล์ SVG  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// บันทึกสไลด์แรกเป็นไฟล์ SVG
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) เมธอด


บันทึกเนื้อหา slide เป็นไฟล์ SVG

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมเป้าหมาย |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | ตัวเลือกการสร้าง SVG |
## หมายเหตุ



ตัวอย่างโค้ดต่อไปนี้แสดงวิธีแปลงสไลด์แรกจากงานนำเสนอ PowerPoint ให้เป็นไฟล์ SVG พร้อมตัวเลือก  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// บันทึกสไลด์แรกเป็นไฟล์ SVG
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Slide](../)
* Class [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)