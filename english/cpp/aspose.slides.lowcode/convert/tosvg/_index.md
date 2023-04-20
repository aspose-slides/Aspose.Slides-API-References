---
title: ToSvg()
second_title: Aspose.Slides for C++ API Reference
description: Converts Presentation to SVG.
type: docs
weight: 27
url: /cpp/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) method


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

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) method


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

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) method


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

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) method


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

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) method


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

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)