---
title: get_Zip64Mode()
second_title: Aspose.Slides for C++ API 參考
description: "指定是否對 Presentation 文件使用 ZIP64 格式。預設值為 Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /zh-hant/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() 方法


指定是否對 [Presentation](../../../aspose.slides/presentation/) 文件使用 ZIP64 格式。預設值為 [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## 另見

* 列舉 [Zip64Mode](../../zip64mode/)
* 類別 [IPptxOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)