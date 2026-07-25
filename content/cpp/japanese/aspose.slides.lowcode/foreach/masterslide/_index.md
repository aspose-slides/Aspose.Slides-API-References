---
title: MasterSlide()
second_title: Aspose.Slides for C++ APIリファレンス
description: "Presentation 内の各 ForEach::MasterSlide を反復します。"
type: docs
weight: 14
url: /ja/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) メソッド

[ForEach::MasterSlide](./)を[Presentation](../../../aspose.slides/presentation/)で反復します。

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) はマスタースライドを反復処理するために使用されます。 |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | マスタースライドごとに呼び出されるコールバック |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [ForEach](../)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)