---
title: get_OutputPath()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "กำหนดว่าทรัพยากรภายนอกควรจะถูกเก็บไว้ที่ใด. อ่าน System::String."
type: docs
weight: 79
url: /th/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() เมธอด


กำหนดว่าทรัพยากรภายนอกควรจะถูกเก็บไว้ที่ใด. อ่าน [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
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
* Library [Aspose.Slides](../../../)