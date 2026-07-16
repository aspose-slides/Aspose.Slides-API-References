---
title: Save()
second_title: Référence API Aspose.Slides pour C++
description: Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié.
type: docs
weight: 404
url: /fr/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) méthode

Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Chemin du fichier créé. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format des données exportées. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) méthode

Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux de sortie. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format des données exportées. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) méthode

Enregistre toutes les diapositives d’une présentation dans un fichier avec le format spécifié et avec des options supplémentaires.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Chemin du fichier créé. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format des données exportées. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Options de format supplémentaires. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) méthode

Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié et avec des options supplémentaires.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux de sortie. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format des données exportées. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Options de format supplémentaires. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) méthode

Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Chemin du fichier créé. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tableau contenant les positions des diapositives, à partir de 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format des données exportées. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) méthode

Enregistre les diapositives spécifiées d’une présentation dans un fichier avec le format spécifié.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Chemin du fichier créé. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tableau contenant les positions des diapositives, à partir de 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format des données exportées. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Options de format supplémentaires. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) méthode

Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux de sortie. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tableau contenant les positions des diapositives, à partir de 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format des données exportées. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) méthode

Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux de sortie. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tableau contenant les positions des diapositives, à partir de 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format des données exportées. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Options de format supplémentaires. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) méthode

Enregistre toutes les diapositives d’une présentation dans un ensemble de fichiers représentant le balisage XAML.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | Les options du format XAML. |

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## Voir aussi

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IPresentation](../)
* Class [Stream](../../../system.io/stream/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)