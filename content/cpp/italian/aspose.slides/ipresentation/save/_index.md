---
title: Save()
second_title: Riferimento API di Aspose.Slides per C++
description: Salva tutte le diapositive di una presentazione in un file con il formato specificato.
type: docs
weight: 404
url: /it/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) method

Salva tutte le diapositive di una presentazione in un file con il formato specificato.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Percorso del file creato. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) method

Salva tutte le diapositive di una presentazione in uno stream nel formato specificato.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di output. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Percorso del file creato. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opzioni aggiuntive del formato. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Salva tutte le diapositive di una presentazione in uno stream nel formato specificato e con opzioni aggiuntive.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di output. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opzioni aggiuntive del formato. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method

Salva le diapositive specificate di una presentazione in un file con il formato specificato.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Percorso del file creato. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array con le posizioni delle diapositive, a partire da 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Salva le diapositive specificate di una presentazione in un file con il formato specificato.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Percorso del file creato. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array con le posizioni delle diapositive, a partire da 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opzioni aggiuntive del formato. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method

Salva le diapositive specificate di una presentazione in uno stream nel formato specificato.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di output. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array con le posizioni delle diapositive, a partire da 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Salva le diapositive specificate di una presentazione in uno stream nel formato specificato.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di output. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array con le posizioni delle diapositive, a partire da 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opzioni aggiuntive del formato. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) method

Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano il markup XAML.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | Le opzioni del formato XAML. |

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## Vedi anche

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [IPresentation](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Classe [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)