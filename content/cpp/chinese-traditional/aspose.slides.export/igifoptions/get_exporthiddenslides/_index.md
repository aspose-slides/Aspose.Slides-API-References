---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 參考
description: 判斷是否會匯出隱藏的投影片。預設值為 false.
type: docs
weight: 27
url: /zh-hant/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() 方法

判斷是否會匯出隱藏的投影片。預設值為 false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 另請參閱

* 類別 [IGifOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)