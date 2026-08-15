---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定在匯出簡報時投影片在頁面上放置的模式 ISlidesLayoutOptions。
type: docs
weight: 378
url: /zh-hant/aspose.slides.export/ipdfoptions/set_slideslayoutoptions/
---
## IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) 方法

設定在匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../islideslayoutoptions/)。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 類別 [IPdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)