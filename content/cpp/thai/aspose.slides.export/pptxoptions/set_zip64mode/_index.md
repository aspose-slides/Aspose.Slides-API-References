---
title: set_Zip64Mode()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "ระบุว่าจะใช้รูปแบบ ZIP64 สำหรับเอกสาร Presentation หรือไม่ ค่าเริ่มต้นคือ Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /th/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) เมธอด

ระบุว่าจะใช้รูปแบบ ZIP64 สำหรับเอกสาร [Presentation](../../../aspose.slides/presentation/) หรือไม่ ค่าตั้งต้นคือ [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
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
* Library [Aspose.Slides](../../../)