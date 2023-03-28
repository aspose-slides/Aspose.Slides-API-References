---
title: ToSvg()
second_title: Aspose.Slides for C++ API Reference
description: Converts Presentation to SVG.
type: docs
weight: 27
url: /cpp/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg([System::String](../../../system/string/)) method


Converts [Presentation](../../../aspose.slides/presentation/) to SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
## Remarks




```cpp
Convert::ToSvg(u"pres.pptx");
```

## See Also

* Class [String](../../../system/string/)
* Class [Convert](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToSvg([System::String](../../../system/string/), [Convert::GetOutPathCallback](../getoutpathcallback/)) method


Converts [Presentation](../../../aspose.slides/presentation/) to SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback that returns the SVG output path for each slide in the presentation |
## Remarks




```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## See Also

* Class [String](../../../system/string/)
* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Class [Convert](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToSvg([System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](../getoutpathcallback/)) method


Converts [Presentation](../../../aspose.slides/presentation/) to SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Callback that returns the SVG output path for each slide in the presentation |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Class [Convert](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToSvg([System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\>) method


Converts [Presentation](../../../aspose.slides/presentation/) to SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG export options |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Class [Convert](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToSvg([System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](../getoutpathcallback/), [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\>) method


Converts [Presentation](../../../aspose.slides/presentation/) to SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback that returns the SVG output path for each slide in the presentation |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG export options |
## Remarks




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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Class [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Class [Convert](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
