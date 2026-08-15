---
title: Compress
second_title: Aspose.Slides for C++ API 參考
description: 代表一組旨在壓縮 Presentation 的方法。
type: docs
weight: 14
url: /zh-hant/aspose.slides.lowcode/compress/
---
## Compress 類別


代表一組旨在壓縮 [Presentation](../../aspose.slides/presentation/) 的方法。

```cpp
class Compress
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 對 [Presentation](../../aspose.slides/presentation/) 進行壓縮，方式為移除嵌入字型中未使用的字元。 |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 對 [Presentation](../../aspose.slides/presentation/) 進行壓縮，方式為移除未使用的版面投影片。 |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 對 [Presentation](../../aspose.slides/presentation/) 進行壓縮，方式為移除未使用的母片投影片。 |
## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 命名空間 [Aspose::Slides::LowCode](../)
* 函式庫 [Aspose.Slides](../../)