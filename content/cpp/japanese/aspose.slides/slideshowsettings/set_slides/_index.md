---
title: set_Slides()
second_title: Aspose.Slides for C++ API リファレンス
description: スライド範囲
type: docs
weight: 131
url: /ja/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) メソッド


[Slides](../../) 範囲

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
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

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [SlidesRange](../../slidesrange/)
* クラス [SlideShowSettings](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)