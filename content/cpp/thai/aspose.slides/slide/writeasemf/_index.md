---
title: WriteAsEmf()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF.
type: docs
weight: 170
url: /th/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) เมธอด


บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### พารามิเตอร์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมเป้าหมาย |
## หมายเหตุ



ตัวอย่างโค้ดด้านล่างแสดงวิธีแปลงสไลด์แรกจากการนำเสนอ PowerPoint ให้เป็นเมตาฟายล์ 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// บันทึกสไลด์แรกเป็นเมตาฟายล์
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## ดูเพิ่มเติม

* คำนิยามประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [Slide](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)