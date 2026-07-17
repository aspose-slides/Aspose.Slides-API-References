---
title: Paragraph()
second_title: Aspose.Slides for C++ API 参考
description: "遍历 Presentation 中的每个 ForEach::Paragraph。"
type: docs
weight: 53
url: /zh/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) 方法

遍历 [Presentation](../../../aspose.slides/presentation/) 中的 [ForEach::Paragraph](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于遍历段落 |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | 将在每个段落上调用的回调 |
## 备注

形状将在所有类型的幻灯片中被遍历 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) 和 [ForEach::LayoutSlide](../layoutslide/)

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

遍历 [Presentation](../../../aspose.slides/presentation/) 中的 [ForEach::Paragraph](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于遍历段落 |
| includeNotes | **bool** | 指示是否应在处理时包含 NotesSlides 的标志 |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | 将在每个段落上调用的回调 |
## 备注

形状将在所有类型的幻灯片中被遍历 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) 和 [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ForEachParagraphCallback](../foreachparagraphcallback/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [ForEach](../)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)