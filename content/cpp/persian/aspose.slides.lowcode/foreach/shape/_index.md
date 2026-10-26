---
title: Shape()
second_title: راهنمای API Aspose.Slides برای C++
description: "هر ForEach::Shape را در Presentation تکرار کنید."
type: docs
weight: 40
url: /fa/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) متد


هر [ForEach::Shape](./) را در [Presentation](../../../aspose.slides/presentation/) تکرید کنید.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای تکرار اشکال طرح‌بندی |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback که برای هر شکل فراخوانی می‌شود |

## توضیحات

اشکال در تمام انواع اسلایدها تکرار می‌شوند - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) و [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) متد


هر [ForEach::Shape](./) را در [Presentation](../../../aspose.slides/presentation/) تکرید کنید.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای تکرار اشکال طرح‌بندی |
| includeNotes | **bool** | پرچمی که نشان می‌دهد آیا NotesSlides باید در پردازش گنجانده شوند یا نه. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback که برای هر شکل فراخوانی می‌شود |

## توضیحات

اشکال در تمام انواع اسلایدها - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) و [NotesSlide](../../../aspose.slides/notesslide/) در صورت نیاز - تکرار می‌شوند.

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) متد


هر [ForEach::Shape](./) را در [BaseSlide](../../../aspose.slides/baseslide/) تکرید کنید.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) برای تکرار اشکال طرح‌بندی |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback که برای هر شکل فراخوانی می‌شود |

## توضیحات

[BaseSlide](../../../aspose.slides/baseslide/) نوع پایه برای [ForEach::Slide](../slide/)، [ForEach::MasterSlide](../masterslide/) و [ForEach::LayoutSlide](../layoutslide/) است.

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

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [ForEach](../)
* کلاس [BaseSlide](../../../aspose.slides/baseslide/)
* فضای نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)