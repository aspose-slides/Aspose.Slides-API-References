---
title: Slide()
second_title: Aspose.Slides for C++ API リファレンス
description: "Presentation の各 ForEach::Slide を反復します。"
type: docs
weight: 1
url: /ja/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) メソッド

[Presentation](../../../aspose.slides/presentation/)内の[ForEach::Slide](./)を反復します。

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) スライドを反復するために |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | 各スライドごとに呼び出されるコールバック |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ForEachSlideCallback](../foreachslidecallback/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [ForEach](../)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)