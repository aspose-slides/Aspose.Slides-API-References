---
title: ToSvg()
second_title: Riferimento API Aspose.Slides per C++
description: Converte Presentation in SVG.
type: docs
weight: 27
url: /it/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) metodo

Converte [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Percorso della presentazione di input |
## Osservazioni

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) metodo

Converte [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Percorso della presentazione di input |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback che restituisce il percorso di output SVG per ogni diapositiva nella presentazione |
## Osservazioni

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) metodo

Converte [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentazione di input |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Callback che restituisce il percorso di output SVG per ogni diapositiva nella presentazione |
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metodo

Converte [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentazione di input |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Opzioni di esportazione SVG |
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metodo

Converte [Presentation](../../../aspose.slides/presentation/) in SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentazione di input |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback che restituisce il percorso di output SVG per ogni diapositiva nella presentazione |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Opzioni di esportazione SVG |
## Osservazioni

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

## Vedi anche

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Spazio dei nomi [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)