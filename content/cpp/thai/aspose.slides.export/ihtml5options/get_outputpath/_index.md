---
title: get_OutputPath()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "กำหนดว่าทรัพยากรภายนอกควรจัดเก็บที่ไหน อ่าน System::String."
type: docs
weight: 79
url: /th/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() เมธอด

กำหนดว่าทรัพยากรภายนอกควรจัดเก็บที่ไหน อ่าน [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
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