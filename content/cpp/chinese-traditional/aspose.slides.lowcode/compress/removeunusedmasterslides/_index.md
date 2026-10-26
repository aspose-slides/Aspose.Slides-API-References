---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides for C++ API 參考
description: 透過移除未使用的母片來壓縮簡報。
type: docs
weight: 1
url: /zh-hant/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) 方法


通過移除未使用的母片來壓縮 [Presentation](../../../aspose.slides/presentation/)。

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 簡報實例 |
## 備註




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [Compress](../)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)