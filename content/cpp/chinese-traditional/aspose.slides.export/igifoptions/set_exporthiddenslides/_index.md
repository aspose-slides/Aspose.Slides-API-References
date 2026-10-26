---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷是否會匯出隱藏的投影片。預設值為 false.
type: docs
weight: 40
url: /zh-hant/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) 方法

判斷是否會匯出隱藏的投影片。預設值為 false。

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 參見

* 類別 [IGifOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)