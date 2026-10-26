---
title: set_Zip64Mode()
second_title: Aspose.Slides C++ API 参考
description: "指定是否对 Presentation 文档使用 ZIP64 格式。默认值为 Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /zh/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) 方法


指定是否对 [Presentation](../../../aspose.slides/presentation/) 文档使用 ZIP64 格式。默认值为 [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
```

## 备注


示例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## 另请参见

* 枚举 [Zip64Mode](../../zip64mode/)
* 类 [IPptxOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)