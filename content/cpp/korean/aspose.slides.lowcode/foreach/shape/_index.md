---
title: Shape()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Presentation에서 각 ForEach::Shape를 반복합니다."
type: docs
weight: 40
url: /ko/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) method


각 [ForEach::Shape](./)를 [Presentation](../../../aspose.slides/presentation/)에서 반복합니다.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 레이아웃 도형을 반복하기 위해 |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 각 shape에 대해 호출될 Callback |
## 비고


모든 유형의 슬라이드에서 Shapes가 반복됩니다 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) 및 [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) method


각 [ForEach::Shape](./)를 [Presentation](../../../aspose.slides/presentation/)에서 반복합니다.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 레이아웃 도형을 반복하기 위해 |
| includeNotes | **bool** | 처리 시 NotesSlides를 포함할지 여부를 나타내는 플래그 |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 각 shape에 대해 호출될 Callback |
## 비고


필요한 경우 모든 유형의 슬라이드에서 Shapes가 반복됩니다 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) 및 [NotesSlide](../../../aspose.slides/notesslide/).



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) method


각 [ForEach::Shape](./)를 [BaseSlide](../../../aspose.slides/baseslide/)에서 반복합니다.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) 레이아웃 도형을 반복하기 위해 |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | 각 shape에 대해 호출될 Callback |
## 비고


[BaseSlide](../../../aspose.slides/baseslide/)은 [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) 및 [ForEach::LayoutSlide](../layoutslide/)의 기본 유형입니다.



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

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Class [BaseSlide](../../../aspose.slides/baseslide/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)