---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides C++ API 参考
description: 确定是否导出隐藏的幻灯片。默认值为 false.
type: docs
weight: 27
url: /zh/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() 方法


确定是否导出隐藏的幻灯片。默认值为 false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## 备注


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## 参见

* 类 [IGifOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)