---
title: get_Zip64Mode()
second_title: Aspose.Slides for C++ API 参考
description: "指定是否对 Presentation 文档使用 ZIP64 格式。默认值是 Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /zh/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() 方法

指定是否对 [Presentation](../../../aspose.slides/presentation/) 文档使用 ZIP64 格式。默认值是 [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## 备注

示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## 另请参见

* Enum [Zip64Mode](../../zip64mode/)
* 类 [IPptxOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)