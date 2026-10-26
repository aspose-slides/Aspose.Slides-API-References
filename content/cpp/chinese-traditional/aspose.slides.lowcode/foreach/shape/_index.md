---
title: Shape()
second_title: Aspose.Slides for C++ API 參考文件
description: "在 Presentation 中遍歷每個 ForEach::Shape。"
type: docs
weight: 40
url: /zh-hant/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) 方法

遍歷 [Presentation](../../../aspose.slides/presentation/) 中的每個 [ForEach::Shape](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用於遍歷版面佈局形狀 |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 回呼函式，將在每個形狀上被調用 |
## 備註

形狀將遍歷所有類型的投影片 - [ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/) 和 [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) 方法

遍歷 [Presentation](../../../aspose.slides/presentation/) 中的每個 [ForEach::Shape](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用於遍歷版面佈局形狀 |
| includeNotes | **bool** | 標誌指示是否應在處理時包含 NotesSlides。 |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 回呼函式，將在每個形狀上被調用 |
## 備註

形狀將遍歷所有類型的投影片 - [ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/)、[ForEach::LayoutSlide](../layoutslide/) 和 [NotesSlide](../../../aspose.slides/notesslide/)（如有需要）。

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) 方法

遍歷 [BaseSlide](../../../aspose.slides/baseslide/) 中的每個 [ForEach::Shape](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) 用於遍歷版面佈局形狀 |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 回呼函式，將在每個形狀上被調用 |
## 備註

[BaseSlide](../../../aspose.slides/baseslide/) 是 [ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/) 和 [ForEach::LayoutSlide](../layoutslide/) 的基礎類型

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

ForEach::Slide(pres, std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> baseSlide, int32_t shapeIndex)
    {
        System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), shapeIndex);
    };

    auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> baseSlide, int32_t shapeIndex)>(lambda);

    ForEach::Shape(slide, callback);
}));
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [ForEach](../)
* 類別 [BaseSlide](../../../aspose.slides/baseslide/)
* 命名空間 [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)