---
title: Save()
second_title: Aspose.Slides voor C++ API-referentie
description: Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat.
type: docs
weight: 404
url: /nl/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) methode


Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Pad naar het aangemaakte bestand. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formaat van de geëxporteerde gegevens. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) methode


Slaat alle dia's van een presentatie op in een stream met het opgegeven formaat.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Uitvoerstroom. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formaat van de geëxporteerde gegevens. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) methode


Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Pad naar het aangemaakte bestand. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formaat van de geëxporteerde gegevens. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Aanvullende formatteringsopties. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) methode


Slaat alle dia's van een presentatie op in een stream met het opgegeven formaat en met extra opties.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Uitvoerstroom. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formaat van de geëxporteerde gegevens. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Aanvullende formatteringsopties. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) methode


Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Pad naar het aangemaakte bestand. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formaat van de geëxporteerde gegevens. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) methode


Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Pad naar het aangemaakte bestand. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formaat van de geëxporteerde gegevens. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Aanvullende formatteringsopties. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) methode


Slaat opgegeven dia's van een presentatie op in een stream met het opgegeven formaat.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Uitvoerstroom. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formaat van de geëxporteerde gegevens. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) methode


Slaat opgegeven dia's van een presentatie op in een stream met het opgegeven formaat.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Uitvoerstroom. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array met dia-posities, beginnend bij 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formaat van de geëxporteerde gegevens. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Aanvullende formatteringsopties. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) methode


Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markup vertegenwoordigen.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | De XAML-formatopties. |
## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Zie ook

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [IPresentation](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Klasse [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)