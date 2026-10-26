---
title: Paragraph()
second_title: Aspose.Slides for C++ API リファレンス
description: "Presentation 内の各 ForEach::Paragraph を反復します。"
type: docs
weight: 53
url: /ja/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) メソッド

[ForEach::Paragraph](./) を [Presentation](../../../aspose.slides/presentation/) 内で反復します。

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 段落を反復するために |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | 各段落に対して呼び出されるコールバック |

## 備考

すべての種類のスライドでシェイプが反復されます - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) および [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) メソッド

[ForEach::Paragraph](./) を [Presentation](../../../aspose.slides/presentation/) 内で反復します。

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 段落を反復するために |
| includeNotes | **bool** | NotesSlides を処理に含めるかどうかを示すフラグ |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | 各段落に対して呼び出されるコールバック |

## 備考

すべての種類のスライドでシェイプが反復されます - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) および [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ForEachParagraphCallback](../foreachparagraphcallback/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [ForEach](../)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)