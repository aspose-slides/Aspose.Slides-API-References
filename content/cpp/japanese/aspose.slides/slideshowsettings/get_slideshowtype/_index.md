---
title: get_SlideShowType()
second_title: Aspose.Slides for C++ API リファレンス
description: "スライドショーのタイプを取得します。次の SlideShowType 先祖によって表されます: BrowsedAtKiosk、PresentedBySpeaker、BrowsedByIndividual"
type: docs
weight: 1
url: /ja/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() メソッド

スライドショーのタイプを取得します。次の[SlideShowType](../../slideshowtype/)先祖によって表されます: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) および [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>();

// "Browsed at a kiosk (full screen)" タイプを設定する
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// "Browsed by individual (window)" タイプを設定する
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// "Presented by a speaker (full screen)" タイプを設定する
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [SlideShowType](../../slideshowtype/)
* クラス [SlideShowSettings](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)