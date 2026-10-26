---
title: Portion()
second_title: Aspose.Slides for C++ API リファレンス
description: "Presentation 内の各 ForEach::Portion を反復処理します。"
type: docs
weight: 66
url: /ja/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) method

[Presentation](../../../aspose.slides/presentation/)内の[ForEach::Portion](./)を反復処理します。

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) をポーションの反復に使用 |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | 各ポーションに対して呼び出されるコールバック |

## 備考

すべてのタイプのスライド（[ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/)、[ForEach::LayoutSlide](../layoutslide/)）でポーションが反復されます。

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) method

[Presentation](../../../aspose.slides/presentation/)内の[ForEach::Portion](./)を反復処理します。

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) をポーションの反復に使用 |
| includeNotes | **bool** | NotesSlides を処理に含めるかどうかを示すフラグ |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | 各ポーションに対して呼び出されるコールバック |

## 備考

すべてのタイプのスライド（[ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/)、[ForEach::LayoutSlide](../layoutslide/)、[NotesSlide](../../../aspose.slides/notesslide/)）でポーションが反復されます。

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [ForEach](../)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)