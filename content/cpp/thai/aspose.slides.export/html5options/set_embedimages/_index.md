---
title: set_EmbedImages()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดตัวเลือกการฝังรูปภาพ. เขียน bool.
type: docs
weight: 66
url: /th/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) เมธอด

กำหนดตัวเลือกการฝังรูปภาพ. เขียน **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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

* คลาส [Html5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)