---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得します ISlidesLayoutOptions.
type: docs
weight: 157
url: /ja/aspose.slides.export/itiffoptions/get_slideslayoutoptions/
---
## ITiffOptions::get_SlidesLayoutOptions() メソッド


プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得します [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ITiffOptions::get_SlidesLayoutOptions()=0
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISlidesLayoutOptions](../../islideslayoutoptions/)
* クラス [ITiffOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)