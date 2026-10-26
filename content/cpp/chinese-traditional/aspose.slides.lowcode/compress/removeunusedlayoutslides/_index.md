---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides for C++ API 參考文件
description: 透過移除未使用的版面投影片，對 Presentation 執行壓縮。
type: docs
weight: 14
url: /zh-hant/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) 方法

透過移除未使用的版面投影片，對 [Presentation](../../../aspose.slides/presentation/) 執行壓縮。

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 簡報實例 |
## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 另請參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [Compress](../)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 程式庫 [Aspose.Slides](../../../)