---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを設定します ISlidesLayoutOptions.
type: docs
weight: 14
url: /ja/aspose.slides.export/pdfoptions/set_slideslayoutoptions/
---
## PdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) メソッド


プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを設定します [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISlidesLayoutOptions](../../islideslayoutoptions/)
* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)