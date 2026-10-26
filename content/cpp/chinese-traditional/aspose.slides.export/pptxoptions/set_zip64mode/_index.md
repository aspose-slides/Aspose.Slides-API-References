---
title: set_Zip64Mode()
second_title: Aspose.Slides for C++ API 參考
description: "指定是否對 Presentation 文件使用 ZIP64 格式。預設值為 Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /zh-hant/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) 方法

指定是否對 [Presentation](../../../aspose.slides/presentation/) 文件使用 ZIP64 格式。預設值為 [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## 另請參閱

* 列舉 [Zip64Mode](../../zip64mode/)
* 類別 [PptxOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)