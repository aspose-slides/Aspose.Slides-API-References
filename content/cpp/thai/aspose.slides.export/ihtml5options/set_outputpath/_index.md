---
title: set_OutputPath()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "กำหนดว่าทรัพยากรภายนอกควรจัดเก็บไว้ที่ใด. เขียน System::String."
type: docs
weight: 92
url: /th/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) เมธอด

กำหนดว่าทรัพยากรภายนอกควรจัดเก็บไว้ที่ใด เขียน [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IHtml5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)