---
title: ToSvg()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: Presentation को SVG में परिवर्तित करता है।
type: docs
weight: 27
url: /hi/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) मेथड

[Presentation](../../../aspose.slides/presentation/) को SVG में परिवर्तित करता है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | इनपुट प्रस्तुति का पथ |
## टिप्पणी

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) मेथड

[Presentation](../../../aspose.slides/presentation/) को SVG में परिवर्तित करता है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | इनपुट प्रस्तुति का पथ |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | प्रत्येक स्लाइड के लिए SVG आउटपुट पथ लौटाने वाला कॉलबैक |
## टिप्पणी

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) मेथड

[Presentation](../../../aspose.slides/presentation/) को SVG में परिवर्तित करता है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >प्रत्येक स्लाइड के लिए SVG आउटपुट पथ लौटाने वाला कॉलबैक |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) मेथड

[Presentation](../../../aspose.slides/presentation/) को SVG में परिवर्तित करता है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG निर्यात विकल्प |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) मेथड

[Presentation](../../../aspose.slides/presentation/) को SVG में परिवर्तित करता है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | प्रत्येक स्लाइड के लिए SVG आउटपुट पथ लौटाने वाला कॉलबैक |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG निर्यात विकल्प |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, callback, svgOptions);
```

## See Also

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Convert](../)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* नामस्थान [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)