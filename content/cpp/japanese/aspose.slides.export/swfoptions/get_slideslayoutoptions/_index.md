---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得します ISlidesLayoutOptions。このプロパティは、タイプ HandoutLayoutingOptions のオブジェクトの割り当てをサポートしません
type: docs
weight: 391
url: /ja/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() メソッド


プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得します [ISlidesLayoutOptions](../../islideslayoutoptions/)。このプロパティは、タイプ [HandoutLayoutingOptions](../../handoutlayoutingoptions/) のオブジェクトの割り当てをサポートしません

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISlidesLayoutOptions](../../islideslayoutoptions/)
* クラス [SwfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)