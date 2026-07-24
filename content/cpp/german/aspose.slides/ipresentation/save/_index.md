---
title: Save()
second_title: Aspose.Slides für C++ API-Referenz
description: Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format.
type: docs
weight: 404
url: /de/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) Methode

Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Pfad zur erstellten Datei. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format der exportierten Daten. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) Methode

Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ausgabestream. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format der exportierten Daten. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) Methode

Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format und zusätzlichen Optionen.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Pfad zur erstellten Datei. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format der exportierten Daten. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Zusätzliche Formatoptionen. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) Methode

Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und zusätzlichen Optionen.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ausgabestream. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format der exportierten Daten. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Zusätzliche Formatoptionen. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) Methode

Speichert angegebene Folien einer Präsentation in einer Datei mit dem angegebenen Format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Pfad zur erstellten Datei. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format der exportierten Daten. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) Methode

Speichert angegebene Folien einer Präsentation in einer Datei mit dem angegebenen Format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Pfad zur erstellten Datei. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format der exportierten Daten. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Zusätzliche Formatoptionen. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) Methode

Speichert angegebene Folien einer Präsentation in einen Stream im angegebenen Format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ausgabestream. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format der exportierten Daten. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) Methode

Speichert angegebene Folien einer Präsentation in einen Stream im angegebenen Format.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ausgabestream. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array mit Folienpositionen, beginnend bei 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format der exportierten Daten. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Zusätzliche Formatoptionen. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) Methode

Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | Die XAML-Formatoptionen. |

## Bemerkungen



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Siehe auch

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [IPresentation](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Klasse [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)