---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを設定します ISlidesLayoutOptions.
type: docs
weight: 14
url: /ja/aspose.slides.export/renderingoptions/set_slideslayoutoptions/
---
## RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) メソッド

プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを設定します [ISlidesLayoutOptions](../../islideslayoutoptions/)。

```cpp
void Aspose::Slides::Export::RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);
slidesLayoutOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> handoutSlides = pres->GetThumbnails(options);
for (int32_t index = 0; index < handoutSlides->get_Length(); index++)
{
    auto handoutSlide = handoutSlides[index];
    handoutSlide->Save(System::String::Format(u"handout-{0}.png", index));
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISlidesLayoutOptions](../../islideslayoutoptions/)
* クラス [RenderingOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)