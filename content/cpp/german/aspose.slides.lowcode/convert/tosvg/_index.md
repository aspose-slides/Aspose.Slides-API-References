---
title: ToSvg()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert Presentation zu SVG.
type: docs
weight: 27
url: /de/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) Methode


Konvertiert [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Pfad der Eingabepräsentation |
## Bemerkungen




```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) Methode


Konvertiert [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Pfad der Eingabepräsentation |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Rückruf, der den SVG-Ausgabepfad für jede Folie in der Präsentation zurückgibt |
## Bemerkungen




```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) Methode


Konvertiert [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Eingabepräsentation |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Rückruf, der den SVG-Ausgabepfad für jede Folie in der Präsentation zurückgibt |
## Bemerkungen




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) Methode


Konvertiert [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Eingabepräsentation |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG-Exportoptionen |
## Bemerkungen




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) Methode


Konvertiert [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Eingabepräsentation |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Rückruf, der den SVG-Ausgabepfad für jede Folie in der Präsentation zurückgibt |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG-Exportoptionen |
## Bemerkungen




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

## Siehe auch

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Convert](../)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namensraum [Aspose::Slides::LowCode](../../)
* Bibliothek [Aspose.Slides](../../../)