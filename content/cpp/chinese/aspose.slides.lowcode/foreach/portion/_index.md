---
title: Portion()
second_title: Aspose.Slides for C++ API 参考
description: "遍历演示文稿中的每个 ForEach::Portion。"
type: docs
weight: 66
url: /zh/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) 方法

遍历 [Presentation](../../../aspose.slides/presentation/) 中的每个 [ForEach::Portion](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于遍历部分 |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | 将在每个部分调用的回调 |

## 备注

所有类型的幻灯片中都会遍历部分 - [ForEach::Slide](../slide/)，[ForEach::MasterSlide](../masterslide/) 和 [ForEach::LayoutSlide](../layoutslide/)

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

遍历 [Presentation](../../../aspose.slides/presentation/) 中的每个 [ForEach::Portion](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于遍历部分 |
| includeNotes | **bool** | 指示是否应在处理时包含 NotesSlides 的标志。 |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | 将在每个部分调用的回调 |

## 备注

所有类型的幻灯片中都会遍历部分 - [ForEach::Slide](../slide/)，[ForEach::MasterSlide](../masterslide/)，[ForEach::LayoutSlide](../layoutslide/) 和 [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [ForEach](../)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)