---
title: ToSvg()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar Presentation till SVG.
type: docs
weight: 27
url: /sv/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) metod


Konverterar [Presentation](../../../aspose.slides/presentation/) till SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Sökväg till inmatningspresentationen |
## Anmärkningar




```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) metod


Konverterar [Presentation](../../../aspose.slides/presentation/) till SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Sökväg till inmatningspresentationen |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback som returnerar SVG-utgångssökvägen för varje bild i presentationen |
## Anmärkningar




```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) metod


Konverterar [Presentation](../../../aspose.slides/presentation/) till SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Inmatningspresentation |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Återuppringning som returnerar SVG-utgångssökvägen för varje bild i presentationen |
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metod


Konverterar [Presentation](../../../aspose.slides/presentation/) till SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Inmatningspresentation |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG-exportalternativ |
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metod


Konverterar [Presentation](../../../aspose.slides/presentation/) till SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Inmatningspresentation |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback som returnerar SVG-utgångssökvägen för varje bild i presentationen |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG-exportalternativ |
## Anmärkningar




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

## Se också

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Convert](../)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Klass [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)