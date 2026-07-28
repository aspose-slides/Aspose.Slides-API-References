---
title: ToSvg()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje prezentację do SVG.
type: docs
weight: 27
url: /pl/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) metoda

Konwertuje [Presentation](../../../aspose.slides/presentation/) do SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Ścieżka prezentacji wejściowej |
## Uwagi

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) metoda

Konwertuje [Presentation](../../../aspose.slides/presentation/) do SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Ścieżka prezentacji wejściowej |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Wywołanie zwrotne, które zwraca ścieżkę wyjściową SVG dla każdego slajdu w prezentacji |
## Uwagi

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) metoda

Konwertuje [Presentation](../../../aspose.slides/presentation/) do SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Prezentacja wejściowa |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Wywołanie zwrotne, które zwraca ścieżkę wyjściową SVG dla każdego slajdu w prezentacji |
## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metoda

Konwertuje [Presentation](../../../aspose.slides/presentation/) do SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Prezentacja wejściowa |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Opcje eksportu SVG |
## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metoda

Konwertuje [Presentation](../../../aspose.slides/presentation/) do SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Prezentacja wejściowa |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Wywołanie zwrotne, które zwraca ścieżkę wyjściową SVG dla każdego slajdu w prezentacji |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Opcje eksportu SVG |
## Uwagi

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

## Zobacz także

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [Convert](../)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Klasa [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Biblioteka [Aspose.Slides](../../../)