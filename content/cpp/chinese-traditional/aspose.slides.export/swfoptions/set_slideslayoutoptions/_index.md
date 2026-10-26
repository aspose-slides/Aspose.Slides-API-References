---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 參考
description: 設定在匯出簡報時投影片在頁面上的放置模式 ISlidesLayoutOptions。此屬性不支援指派類型為 HandoutLayoutingOptions 的物件
type: docs
weight: 404
url: /zh-hant/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) 方法

設定在匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../islideslayoutoptions/)。此屬性不支援指派類型為 [HandoutLayoutingOptions](../../handoutlayoutingoptions/) 的物件

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 類別 [SwfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)