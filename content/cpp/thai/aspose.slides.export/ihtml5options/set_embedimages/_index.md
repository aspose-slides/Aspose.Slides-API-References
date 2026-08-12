---
title: set_EmbedImages()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: กำหนดตัวเลือกการฝังรูปภาพ เขียน bool.
type: docs
weight: 66
url: /th/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) เมธอด


ตั้งค่าตัวเลือกการฝังรูปภาพ เขียน **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## ดูเพิ่มเติม

* คลาส [IHtml5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)