---
title: LayoutSlide()
second_title: Aspose.Slides for C++ API リファレンス
description: "Presentation内の各 ForEach::LayoutSlide を反復します。"
type: docs
weight: 27
url: /ja/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) メソッド

[ForEach::LayoutSlide](./) を [Presentation](../../../aspose.slides/presentation/) で反復します。

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) はレイアウトスライドを反復するためのもの |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | 各レイアウトスライドに対して呼び出されるコールバック |

## 備考


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [ForEach](../)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)