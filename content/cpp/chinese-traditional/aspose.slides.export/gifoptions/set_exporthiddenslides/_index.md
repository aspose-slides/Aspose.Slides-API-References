---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 參考
description: 判斷是否會匯出隱藏投影片。預設值為 false.
type: docs
weight: 40
url: /zh-hant/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) 方法

判斷是否會匯出隱藏的投影片。預設值為 false。

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 另見

* 類別 [GifOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)