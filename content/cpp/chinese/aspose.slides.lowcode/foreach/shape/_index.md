---
title: Shape()
second_title: Aspose.Slides for C++ API 参考
description: "迭代 Presentation 中的每个 ForEach::Shape。"
type: docs
weight: 40
url: /zh/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) 方法

遍历 [Presentation](../../../aspose.slides/presentation/) 中的每个 [ForEach::Shape](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于遍历布局形状 |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 在每个形状上调用的回调 |

## 备注

将在所有类型的幻灯片中遍历形状 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) 和 [ForEach::LayoutSlide](../layoutslide/)

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

遍历 [Presentation](../../../aspose.slides/presentation/) 中的每个 [ForEach::Shape](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于遍历布局形状 |
| includeNotes | **bool** | 标志，指示是否应在处理时包括 NotesSlides。 |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 在每个形状上调用的回调 |

## 备注

将在所有类型的幻灯片中遍历形状 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) 和 [NotesSlide](../../../aspose.slides/notesslide/)（如有需要）。

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

遍历 [BaseSlide](../../../aspose.slides/baseslide/) 中的每个 [ForEach::Shape](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) 用于遍历布局形状 |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 在每个形状上调用的回调 |

## 备注

[BaseSlide](../../../aspose.slides/baseslide/) 是 [ForEach::Slide](../slide/)、[ForEach::MasterSlide](../masterslide/) 和 [ForEach::LayoutSlide](../layoutslide/) 的基类型。

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

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ForEachShapeCallback](../foreachshapecallback/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [ForEach](../)
* 类 [BaseSlide](../../../aspose.slides/baseslide/)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)