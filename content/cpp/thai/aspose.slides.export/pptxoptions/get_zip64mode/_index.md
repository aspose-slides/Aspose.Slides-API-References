---
title: get_Zip64Mode()
second_title: Aspose.Slides สำหรับ API อ้างอิงของ C++
description: "ระบุว่ารูปแบบ ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ ค่าเริ่มต้นคือ Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /th/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() เมธอด


ระบุว่าใช้รูปแบบ ZIP64 สำหรับเอกสาร [Presentation](../../../aspose.slides/presentation/) หรือไม่ ค่าตั้งต้นคือ [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
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
* คลาส [PptxOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)