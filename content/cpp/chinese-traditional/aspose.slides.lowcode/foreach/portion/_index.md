---
title: Portion()
second_title: Aspose.Slides for C++ API 參考
description: "遍歷 Presentation 中的每個 ForEach::Portion。"
type: docs
weight: 66
url: /zh-hant/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) 方法

遍歷 [Presentation](../../../aspose.slides/presentation/) 中的每個 [ForEach::Portion](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用於遍歷部分 |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | 在每個部分被呼叫的回呼 |

## 備註

將會在所有類型的投影片中遍歷部分 - [ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/) 和 [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) 方法

遍歷 [Presentation](../../../aspose.slides/presentation/) 中的每個 [ForEach::Portion](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用於遍歷部分 |
| includeNotes | **bool** | 指示是否應在處理時包含 NotesSlides 的旗標。 |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | 在每個部分被呼叫的回呼 |

## 備註

將會在所有類型的投影片中遍歷部分 - [ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/)、[ForEach::LayoutSlide](../layoutslide/) 和 [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ForEachPortionCallback](../foreachportioncallback/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [ForEach](../)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)