---
title: set_OutputPath()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "กำหนดว่าข้อมูลภายนอกควรจัดเก็บที่ไหน เขียน System::String."
type: docs
weight: 92
url: /th/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) เมธอด


กำหนดว่าแหล่งข้อมูลภายนอกควรจัดเก็บที่ไหน เขียน [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [Html5Options](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)