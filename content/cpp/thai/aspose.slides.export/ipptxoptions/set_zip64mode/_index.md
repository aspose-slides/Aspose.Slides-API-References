---
title: set_Zip64Mode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ระบุว่ารูปแบบ ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ ค่าตั้งต้นคือ Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /th/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) เมธอด


ระบุว่ารูปแบบ ZIP64 ถูกใช้สำหรับเอกสาร [Presentation](../../../aspose.slides/presentation/) หรือไม่ ค่าตั้งต้นคือ [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
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
* เนมส페ซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)