---
title: Save()
second_title: Aspose.Slides for C++ – dokumentacja API
description: Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie.
type: docs
weight: 404
url: /pl/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) metoda

Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Ścieżka do tworzonego pliku. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format eksportowanych danych. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) metoda

Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wyjściowy. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format eksportowanych danych. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metoda

Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie oraz z dodatkowymi opcjami.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Ścieżka do tworzonego pliku. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format eksportowanych danych. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Dodatkowe opcje formatu. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metoda

Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie oraz z dodatkowymi opcjami.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wyjściowy. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format eksportowanych danych. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Dodatkowe opcje formatu. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) metoda

Zapisuje określone slajdy prezentacji do pliku w określonym formacie.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Ścieżka do tworzonego pliku. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, począwszy od 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format eksportowanych danych. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metoda

Zapisuje określone slajdy prezentacji do pliku w określonym formacie.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Ścieżka do tworzonego pliku. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, począwszy od 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format eksportowanych danych. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Dodatkowe opcje formatu. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) metoda

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wyjściowy. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, począwszy od 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format eksportowanych danych. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metoda

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wyjściowy. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tablica z pozycjami slajdów, począwszy od 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format eksportowanych danych. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Dodatkowe opcje formatu. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) metoda

Zapisuje wszystkie slajdy prezentacji do zestawu plików reprezentujących znaczniki XAML.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | Opcje formatu XAML. |

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Zobacz także

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [IPresentation](../)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Klasa [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)