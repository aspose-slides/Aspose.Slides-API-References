---
title: ToSvg()
second_title: Referência da API Aspose.Slides para C++
description: Converte Presentation para SVG.
type: docs
weight: 27
url: /pt/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) método

Converte [Presentation](../../../aspose.slides/presentation/) para SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Caminho da apresentação de entrada |
## Observações

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) método

Converte [Presentation](../../../aspose.slides/presentation/) para SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Caminho da apresentação de entrada |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback que devolve o caminho de saída SVG para cada slide da apresentação |
## Observações

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) método

Converte [Presentation](../../../aspose.slides/presentation/) para SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Apresentação de entrada |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Callback que devolve o caminho de saída SVG para cada slide da apresentação |
## Observações

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) método

Converte [Presentation](../../../aspose.slides/presentation/) para SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Apresentação de entrada |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Opções de exportação SVG |
## Observações

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) método

Converte [Presentation](../../../aspose.slides/presentation/) para SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Apresentação de entrada |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback que devolve o caminho de saída SVG para cada slide da apresentação |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Opções de exportação SVG |
## Observações

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

## Veja Também

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)