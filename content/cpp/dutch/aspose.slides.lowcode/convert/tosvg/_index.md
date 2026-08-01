---
title: ToSvg()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert presentatie naar SVG.
type: docs
weight: 27
url: /nl/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) methode

Converteert [Presentation](../../../aspose.slides/presentation/) naar SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Pad van de invoerpresentatie |
## Opmerkingen

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) methode

Converteert [Presentation](../../../aspose.slides/presentation/) naar SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Pad van de invoerpresentatie |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback die het SVG-uitvoerpad voor elke dia in de presentatie retourneert |
## Opmerkingen

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) methode

Converteert [Presentation](../../../aspose.slides/presentation/) naar SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Invoerpresentatie |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Callback die het SVG-uitvoerpad voor elke dia in de presentatie retourneert |
## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) methode

Converteert [Presentation](../../../aspose.slides/presentation/) naar SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Invoerpresentatie |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG-exportopties |
## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) methode

Converteert [Presentation](../../../aspose.slides/presentation/) naar SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Invoerpresentatie |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback die het SVG-uitvoerpad voor elke dia in de presentatie retourneert |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG-exportopties |
## Opmerkingen

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

## Zie ook

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Convert](../)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)