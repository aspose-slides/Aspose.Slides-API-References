---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides 於 C++ API 參考文件
description: 取得在匯出簡報時投影片在頁面上放置的模式 ISlidesLayoutOptions。本屬性不支援指派 HandoutLayoutingOptions 類型的物件
type: docs
weight: 391
url: /zh-hant/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() 方法


取得匯出簡報時投影片在頁面上放置的模式 [ISlidesLayoutOptions](../../islideslayoutoptions/)。此屬性不支援指派類型為 [HandoutLayoutingOptions](../../handoutlayoutingoptions/) 的物件

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 類別 [SwfOptions](../)
* 名稱空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)