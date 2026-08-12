---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ เอกสารอ้างอิง API
description: รับโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกงานนำเสนอ ISlidesLayoutOptions.
type: docs
weight: 157
url: /th/aspose.slides.export/html5options/get_slideslayoutoptions/
---
## Html5Options::get_SlidesLayoutOptions() เมธอด

รับโหมดที่สไลด์จะวางบนหน้าขณะส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::Html5Options::get_SlidesLayoutOptions() override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlidesLayoutOptions](../../islideslayoutoptions/)
* คลาส [Html5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)