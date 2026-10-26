---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 参考
description: 确定是否导出隐藏的幻灯片。默认值为 false。
type: docs
weight: 27
url: /zh/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() 方法


确定是否导出隐藏的幻灯片。默认值为 false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## 另请参阅

* 类 [GifOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)