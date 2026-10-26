---
title: ToSvg()
second_title: Aspose.Slides for C++ API referencia
description: Átalakítja a prezentációt SVG formátumba.
type: docs
weight: 27
url: /hu/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) metódus

Átalakítja a [Presentation](../../../aspose.slides/presentation/) SVG formátumba.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | A bemeneti prezentáció útvonala |
## Megjegyzés




```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) metódus

Átalakítja a [Presentation](../../../aspose.slides/presentation/) SVG formátumba.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | A bemeneti prezentáció útvonala |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Visszahívás, amely visszaadja az SVG kimeneti útvonalat a prezentáció egyes diáihoz |
## Megjegyzés




```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) metódus

Átalakítja a [Presentation](../../../aspose.slides/presentation/) SVG formátumba.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Bemeneti prezentáció |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Visszahívás, amely visszaadja az SVG kimeneti útvonalat a prezentáció egyes diáihoz |
## Megjegyzés 




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metódus

Átalakítja a [Presentation](../../../aspose.slides/presentation/) SVG formátumba.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Bemeneti prezentáció |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG exportálási beállítások |
## Megjegyzés




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metódus

Átalakítja a [Presentation](../../../aspose.slides/presentation/) SVG formátumba.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Bemeneti prezentáció |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Visszahívás, amely visszaadja az SVG kimeneti útvonalat a prezentáció egyes diáihoz |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG exportálási beállítások |
## Megjegyzés 




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

## Lásd még

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Convert](../)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Névtér [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)