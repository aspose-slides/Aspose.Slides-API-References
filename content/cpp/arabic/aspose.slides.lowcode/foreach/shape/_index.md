---
title: Shape()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "تكرار كل ForEach::Shape في العرض التقديمي."
type: docs
weight: 40
url: /ar/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) method


تكرار كل [ForEach::Shape](./) في [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) لتكرار أشكال التخطيط |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | الدالة الراجعة التي سيتم استدعاؤها لكل شكل |
## ملاحظات


سيتم تكرار الأشكال في جميع أنواع الشرائح - [ForEach::Slide](../slide/)، [ForEach::MasterSlide](../masterslide/) و [ForEach::LayoutSlide](../layoutslide/)



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


تكرار كل [ForEach::Shape](./) في [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) لتكرار أشكال التخطيط |
| includeNotes | **bool** | علامة توضح ما إذا كان يجب تضمين شرائح الملاحظات في المعالجة. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | الدالة الراجعة التي سيتم استدعاؤها لكل شكل |
## ملاحظات


سيتم تكرار الأشكال في جميع أنواع الشرائح - [ForEach::Slide](../slide/)، [ForEach::MasterSlide](../masterslide/)، [ForEach::LayoutSlide](../layoutslide/) و [NotesSlide](../../../aspose.slides/notesslide/) إذا لزم الأمر.



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


تكرار كل [ForEach::Shape](./) في [BaseSlide](../../../aspose.slides/baseslide/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) لتكرار أشكال التخطيط |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | الدالة الراجعة التي سيتم استدعاؤها لكل شكل |
## ملاحظات


[BaseSlide](../../../aspose.slides/baseslide/) هو النوع الأساسي لـ [ForEach::Slide](../slide/)، [ForEach::MasterSlide](../masterslide/) و [ForEach::LayoutSlide](../layoutslide/)



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

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [ForEach](../)
* فئة [BaseSlide](../../../aspose.slides/baseslide/)
* مساحة اسم [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)