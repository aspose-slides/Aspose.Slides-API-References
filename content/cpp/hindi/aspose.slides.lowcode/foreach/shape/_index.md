---
title: Shape()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Presentation में प्रत्येक ForEach::Shape को दोहराएँ।"
type: docs
weight: 40
url: /hi/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) विधि

प्रत्येक [ForEach::Shape](./) को [Presentation](../../../aspose.slides/presentation/) में दोहराएँ।

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | लेआउट shapes को दोहराने के लिए [Presentation](../../../aspose.slides/presentation/) |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | प्रत्येक shape के लिए कॉल किया जाने वाला कॉलबैक |

## टिप्पणियाँ

Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) और [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) विधि

प्रत्येक [ForEach::Shape](./) को [Presentation](../../../aspose.slides/presentation/) में दोहराएँ।

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | लेआउट shapes को दोहराने के लिए [Presentation](../../../aspose.slides/presentation/) |
| includeNotes | **bool** | एक फ़्लैग जो दर्शाता है कि NotesSlides को प्रक्रिया में शामिल किया जाना चाहिए या नहीं। |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | प्रत्येक shape के लिए कॉल किया जाने वाला कॉलबैक |

## टिप्पणियाँ

Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) और [NotesSlide](../../../aspose.slides/notesslide/) यदि आवश्यक हो।

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) विधि

प्रत्येक [ForEach::Shape](./) को [BaseSlide](../../../aspose.slides/baseslide/) में दोहराएँ।

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | लेआउट shapes को दोहराने के लिए [Slide](../../../aspose.slides/slide/) |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | प्रत्येक shape के लिए कॉल किया जाने वाला कॉलबैक |

## टिप्पणियाँ

[BaseSlide](../../../aspose.slides/baseslide/) बेस टाइप है [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) और [ForEach::LayoutSlide](../layoutslide/) के लिए।

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

## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Class [BaseSlide](../../../aspose.slides/baseslide/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)