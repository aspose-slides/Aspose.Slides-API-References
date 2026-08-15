---
title: get_Zip64Mode()
second_title: Aspose.Slides for C++ API 參考
description: "指定是否對 Presentation 文件使用 ZIP64 格式。預設值為 Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /zh-hant/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() 方法

指定是否對 [Presentation](../../../aspose.slides/presentation/) 文件使用 ZIP64 格式。預設值為 [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## 參見

* Enum [Zip64Mode](../../zip64mode/)
* 類別 [PptxOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)