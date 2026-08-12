---
title: get_Zip64Mode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ระบุว่ารูปแบบ ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ ค่าเริ่มต้นคือ Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /th/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() เมธอด


ระบุว่ารูปแบบ ZIP64 ถูกใช้สำหรับเอกสาร [Presentation](../../../aspose.slides/presentation/) หรือไม่ ค่าปริยายคือ [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## ดูเพิ่มเติม

* Enum [Zip64Mode](../../zip64mode/)
* คลาส [IPptxOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)