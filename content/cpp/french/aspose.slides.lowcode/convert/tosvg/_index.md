---
title: ToSvg()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la présentation en SVG.
type: docs
weight: 27
url: /fr/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) méthode

Convertit [Presentation](../../../aspose.slides/presentation/) en SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Chemin de la présentation d’entrée |

## Remarques

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) méthode

Convertit [Presentation](../../../aspose.slides/presentation/) en SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Chemin de la présentation d’entrée |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Fonction de rappel qui renvoie le chemin de sortie SVG pour chaque diapositive de la présentation |

## Remarques

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) méthode

Convertit [Presentation](../../../aspose.slides/presentation/) en SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Présentation d’entrée |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Fonction de rappel qui renvoie le chemin de sortie SVG pour chaque diapositive de la présentation |

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) méthode

Convertit [Presentation](../../../aspose.slides/presentation/) en SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Présentation d’entrée |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Options d’exportation SVG |

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) méthode

Convertit [Presentation](../../../aspose.slides/presentation/) en SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Présentation d’entrée |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Fonction de rappel qui renvoie le chemin de sortie SVG pour chaque diapositive de la présentation |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Options d’exportation SVG |

## Remarques

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

## Voir aussi

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Espace de noms [Aspose::Slides::LowCode](../../)
* Bibliothèque [Aspose.Slides](../../../)