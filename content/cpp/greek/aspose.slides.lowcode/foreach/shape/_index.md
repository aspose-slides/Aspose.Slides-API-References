---
title: Shape()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Επανάληψη κάθε ForEach::Shape στην Παρουσίαση."
type: docs
weight: 40
url: /el/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) method


Επανάλαβε κάθε [ForEach::Shape](./) στο [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) to iterate layout shapes |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback that will be invoked for each shape |
## Παρατηρήσεις


Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) και [ForEach::LayoutSlide](../layoutslide/)



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


Επανάλαβε κάθε [ForEach::Shape](./) στο [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) to iterate layout shapes |
| includeNotes | **bool** | Flag that indicates whether NotesSlides should be included in processing. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback that will be invoked for each shape |
## Παρατηρήσεις


Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) και [NotesSlide](../../../aspose.slides/notesslide/) εάν απαιτείται.



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


Επανάλαβε κάθε [ForEach::Shape](./) στο [BaseSlide](../../../aspose.slides/baseslide/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) to iterate layout shapes |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback that will be invoked for each shape |
## Παρατηρήσεις


[BaseSlide](../../../aspose.slides/baseslide/) είναι ο βασικός τύπος για [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) και [ForEach::LayoutSlide](../layoutslide/)



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

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Κλάση [Presentation](../../../aspose.slides/presentation/)
* Κλάση [ForEach](../)
* Κλάση [BaseSlide](../../../aspose.slides/baseslide/)
* Χώρος ονομάτων [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)