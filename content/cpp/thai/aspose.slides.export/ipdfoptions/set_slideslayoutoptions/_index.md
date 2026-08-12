---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกการนำเสนอ ISlidesLayoutOptions.
type: docs
weight: 378
url: /th/aspose.slides.export/ipdfoptions/set_slideslayoutoptions/
---
## IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) เมธอด

กำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## ดูเพิ่มเติม

* ชนิดกำหนด [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlidesLayoutOptions](../../islideslayoutoptions/)
* คลาส [IPdfOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)