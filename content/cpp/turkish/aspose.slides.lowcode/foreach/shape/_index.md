---
title: Shape()
second_title: Aspose.Slides for C++ API Referansı
description: "Sunumda her bir ForEach::Shape yineleyin."
type: docs
weight: 40
url: /tr/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) metot


[Presentation](../../../aspose.slides/presentation/) içinde her bir [ForEach::Shape](./) yineleyin.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) layout şekillerini yinelemek için |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | her şekil için çağrılacak geri arama |
## Açıklamalar

Şekiller, tüm slayt tiplerinde yineleyecektir - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) ve [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) metot


[Presentation](../../../aspose.slides/presentation/) içinde her bir [ForEach::Shape](./) yineleyin.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) layout şekillerini yinelemek için |
| includeNotes | **bool** | Not Slaytlarının işleme dahil edilip edilmediğini gösteren bayrak. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | her şekil için çağrılacak geri arama |
## Açıklamalar

Şekiller, gerektiğinde tüm slayt tiplerinde yineleyecektir - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) ve [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) metot


[BaseSlide](../../../aspose.slides/baseslide/) içinde her bir [ForEach::Shape](./) yineleyin.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) layout şekillerini yinelemek için |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | her şekil için çağrılacak geri arama |
## Açıklamalar

[BaseSlide](../../../aspose.slides/baseslide/) [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) ve [ForEach::LayoutSlide](../layoutslide/) için temel türdür

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

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [ForEach](../)
* Sınıf [BaseSlide](../../../aspose.slides/baseslide/)
* Ad alanı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)