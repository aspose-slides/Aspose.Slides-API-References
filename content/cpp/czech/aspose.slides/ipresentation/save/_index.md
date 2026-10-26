---
title: Save()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Uloží všechny snímky prezentace do souboru ve specifikovaném formátu.
type: docs
weight: 404
url: /cs/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) method


Uloží všechny snímky prezentace do souboru ve specifikovaném formátu.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Cesta k vytvořenému souboru. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formát exportovaných dat. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) method


Uloží všechny snímky prezentace do proudu ve specifikovaném formátu.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Výstupní proud. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formát exportovaných dat. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


Uloží všechny snímky prezentace do souboru ve specifikovaném formátu a s dalšími možnostmi.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Cesta k vytvořenému souboru. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formát exportovaných dat. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Další volby formátu. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


Uloží všechny snímky prezentace do proudu ve specifikovaném formátu a s dalšími možnostmi.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Výstupní proud. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formát exportovaných dat. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Další volby formátu. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method


Uloží určené snímky prezentace do souboru ve specifikovaném formátu.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Cesta k vytvořenému souboru. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formát exportovaných dat. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


Uloží určené snímky prezentace do souboru ve specifikovaném formátu.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Cesta k vytvořenému souboru. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formát exportovaných dat. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Další volby formátu. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method


Uloží určené snímky prezentace do proudu ve specifikovaném formátu.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Výstupní proud. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formát exportovaných dat. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


Uloží určené snímky prezentace do proudu ve specifikovaném formátu.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Výstupní proud. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Pole s pozicemi snímků, počínaje 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formát exportovaných dat. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Další volby formátu. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) method


Uloží všechny snímky prezentace do sady souborů představujících XAML zápis.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | Volby formátu XAML. |
## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Viz také

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