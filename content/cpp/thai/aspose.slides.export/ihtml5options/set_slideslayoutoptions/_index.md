---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดโหมดที่สไลด์จะถูกวางบนหน้าเมื่อส่งออกการนำเสนอ ISlidesLayoutOptions.
type: docs
weight: 170
url: /th/aspose.slides.export/ihtml5options/set_slideslayoutoptions/
---
## IHtml5Options::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method


ตั้งค่ารูปแบบที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## ดูเพิ่มเติม

* ประเภทกำหนดใหม่ [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlidesLayoutOptions](../../islideslayoutoptions/)
* คลาส [IHtml5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)