---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 參考
description: 取得在匯出簡報時投影片放置於頁面上的模式 ISlidesLayoutOptions.
type: docs
weight: 157
url: /zh-hant/aspose.slides.export/html5options/get_slideslayoutoptions/
---
## Html5Options::get_SlidesLayoutOptions() 方法

取得在匯出簡報時投影片放置於頁面上的模式 [ISlidesLayoutOptions](../../islideslayoutoptions/)。

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::Html5Options::get_SlidesLayoutOptions() override
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 類別 [Html5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)