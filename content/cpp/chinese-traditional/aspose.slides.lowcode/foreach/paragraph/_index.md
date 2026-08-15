---
title: Paragraph()
second_title: Aspose.Slides for C++ API 參考
description: "遍歷 Presentation 中的每個 ForEach::Paragraph。"
type: docs
weight: 53
url: /zh-hant/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) 方法

遍歷 [Presentation](../../../aspose.slides/presentation/) 中的每個 [ForEach::Paragraph](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 以遍歷段落 |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | 每個段落將呼叫的回呼函式 |

## 備註

所有類型的投影片中的形狀皆會被遍歷 - [ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/) 和 [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) 方法

遍歷 [Presentation](../../../aspose.slides/presentation/) 中的每個 [ForEach::Paragraph](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 以遍歷段落 |
| includeNotes | **bool** | 指示是否將 NotesSlides 包含在處理中的旗標。 |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | 每個段落將呼叫的回呼函式 |

## 備註

所有類型的投影片中的形狀皆會被遍歷 - [ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/)、[ForEach::LayoutSlide](../layoutslide/) 和 [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ForEachParagraphCallback](../foreachparagraphcallback/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [ForEach](../)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)