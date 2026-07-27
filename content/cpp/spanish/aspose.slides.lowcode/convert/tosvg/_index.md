---
title: ToSvg()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte Presentation a SVG.
type: docs
weight: 27
url: /es/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) método

Convierte [Presentation](../../../aspose.slides/presentation/) a SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Ruta de la presentación de entrada |

## Observaciones

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) método

Convierte [Presentation](../../../aspose.slides/presentation/) a SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Ruta de la presentación de entrada |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback que devuelve la ruta de salida SVG para cada diapositiva de la presentación |

## Observaciones

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) método

Convierte [Presentation](../../../aspose.slides/presentation/) a SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentación de entrada |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Callback que devuelve la ruta de salida SVG para cada diapositiva de la presentación |

## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) método

Convierte [Presentation](../../../aspose.slides/presentation/) a SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentación de entrada |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Opciones de exportación SVG |

## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) método

Convierte [Presentation](../../../aspose.slides/presentation/) a SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentación de entrada |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback que devuelve la ruta de salida SVG para cada diapositiva de la presentación |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Opciones de exportación SVG |

## Observaciones

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

## Ver también

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [Convert](../)
* Clase [Presentation](../../../aspose.slides/presentation/)
* Clase [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)