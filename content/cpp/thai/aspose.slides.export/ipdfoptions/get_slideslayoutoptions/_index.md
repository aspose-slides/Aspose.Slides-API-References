---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ ISlidesLayoutOptions.
type: docs
weight: 365
url: /th/aspose.slides.export/ipdfoptions/get_slideslayoutoptions/
---
## IPdfOptions::get_SlidesLayoutOptions() เมธอด

รับโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IPdfOptions::get_SlidesLayoutOptions()=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlidesLayoutOptions](../../islideslayoutoptions/)
* คลาส [IPdfOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)