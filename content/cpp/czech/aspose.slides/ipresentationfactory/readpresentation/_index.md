---
title: ReadPresentation()
second_title: Aspose.Slides pro C++ API Reference
description: Načte existující prezentaci z pole
type: docs
weight: 27
url: /cs/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metoda


Načte existující prezentaci z pole

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole k načtení |

### Návratová hodnota

Načtená prezentace

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metoda


Načte existující prezentaci z pole s doplňkovými možnostmi načtení

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole k načtení |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Možnosti načtení |

### Návratová hodnota

Načtená prezentace

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metoda


Načte existující prezentaci ze streamu

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní stream k načtení |

### Návratová hodnota

Načtená prezentace

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metoda


Načte existující prezentaci ze streamu s doplňkovými možnostmi načtení

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní stream k načtení |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Možnosti načtení |

### Návratová hodnota

Načtená prezentace

## IPresentationFactory::ReadPresentation(System::String) metoda


Načte existující prezentaci ze souboru

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Název souboru |

### Návratová hodnota

Načtená prezentace

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metoda


Načte existující prezentaci ze streamu s doplňkovými možnostmi načtení

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
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
* Třída [IPresentation](../../ipresentation/)
* Třída [IPresentationFactory](../)
* Třída [ILoadOptions](../../iloadoptions/)
* Třída [Stream](../../../system.io/stream/)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)