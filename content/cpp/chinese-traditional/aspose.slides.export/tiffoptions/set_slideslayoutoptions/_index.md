---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 參考
description: 設定在匯出簡報時，投影片在頁面上的放置模式 ISlidesLayoutOptions.
type: docs
weight: 183
url: /zh-hant/aspose.slides.export/tiffoptions/set_slideslayoutoptions/
---
## TiffOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method

設定在匯出簡報時，投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## 備註

範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 類別 [TiffOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)