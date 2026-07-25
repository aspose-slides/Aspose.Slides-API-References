---
title: set_PrintComments()
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上にコメントを表示するかどうかを指定します
type: docs
weight: 92
url: /ja/aspose.slides.export/handoutlayoutingoptions/set_printcomments/
---
## HandoutLayoutingOptions::set_PrintComments(bool) メソッド


スライド上にコメントを表示するかどうかを指定します

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintComments(bool value)
```

## 備考


デフォルト値は **false**.

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintComments(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## 関連項目

* クラス [HandoutLayoutingOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)