---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดโหมดที่สไลด์จะถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ ISlidesLayoutOptions. คุณสมบัตินี้ไม่รองรับการกำหนดวัตถุประเภท HandoutLayoutingOptions
type: docs
weight: 404
url: /th/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) เมธอด

กำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../islideslayoutoptions/). คุณสมบัตินี้ไม่รองรับการกำหนดวัตถุของประเภท [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlidesLayoutOptions](../../islideslayoutoptions/)
* คลาส [SwfOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)