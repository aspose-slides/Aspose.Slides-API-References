---
title: get_Slides()
second_title: Aspose.Slides for C++ API リファレンス
description: スライドの範囲
type: docs
weight: 118
url: /ja/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const メソッド


[Slides](../../) 範囲

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [SlidesRange](../../slidesrange/)
* クラス [SlideShowSettings](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)