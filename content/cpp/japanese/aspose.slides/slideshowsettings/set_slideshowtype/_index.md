---
title: set_SlideShowType()
second_title: Aspose.Slides for C++ API リファレンス
description: "スライドショーのタイプを設定します。次の SlideShowType の先祖: BrowsedAtKiosk, PresentedBySpeaker および BrowsedByIndividual によって表されます"
type: docs
weight: 14
url: /ja/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) メソッド


スライドショーのタイプを設定します。次の[SlideShowType](../../slideshowtype/)先祖: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) と [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>();

// 「Browsed at a kiosk (full screen)」タイプを設定
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// 「Browsed by individual (window)」タイプを設定
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// 「Presented by a speaker (full screen)」タイプを設定
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [SlideShowType](../../slideshowtype/)
* クラス [SlideShowSettings](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)