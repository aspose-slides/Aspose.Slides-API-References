---
title: ReadPresentation()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Načte existující prezentaci z pole
type: docs
weight: 40
url: /cs/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metoda


Načte existující prezentaci z pole

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole k načtení |

### Návratová hodnota

Načtená prezentace

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metoda


Načte existující prezentaci z pole s dalšími možnostmi načtení

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole k načtení |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Možnosti načtení |

### Návratová hodnota

Načtená prezentace

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metoda


Načte existující prezentaci ze streamu

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní stream k načtení |

### Návratová hodnota

Načtená prezentace

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metoda


Načte existující prezentaci ze streamu s dalšími možnostmi načtení

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní stream k načtení |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Možnosti načtení |

### Návratová hodnota

Načtená prezentace

## PresentationFactory::ReadPresentation(System::String) metoda


Načte existující prezentaci ze souboru

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Název souboru |

### Návratová hodnota

Načtená prezentace

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metoda


Načte existující prezentaci ze streamu s dalšími možnostmi načtení

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Název souboru |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Možnosti načtení |

### Návratová hodnota

Načtená prezentace

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPresentation](../../ipresentation/)
* Class [PresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)