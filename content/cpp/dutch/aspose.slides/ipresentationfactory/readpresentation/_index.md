---
title: ReadPresentation()
second_title: Aspose.Slides voor C++ API Referentie
description: Leest een bestaande presentatie uit een array
type: docs
weight: 27
url: /nl/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) methode


Leest een bestaande presentatie uit een array

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array om te lezen |

### Retourwaarde

Leest presentatie

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) methode


Leest een bestaande presentatie uit een array met extra laadopties

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array om te lezen |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Laadopties |

### Retourwaarde

Leest presentatie

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) methode


Leest een bestaande presentatie uit een stream

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Invoerstroom om te lezen |

### Retourwaarde

Leest presentatie

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) methode


Leest een bestaande presentatie uit een stream met extra laadopties

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Invoerstroom om te lezen |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Laadopties |

### Retourwaarde

Leest presentatie

## IPresentationFactory::ReadPresentation(System::String) methode


Leest een bestaande presentatie uit een bestand

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Bestandsnaam |

### Retourwaarde

Leest presentatie

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) methode


Leest een bestaande presentatie uit een stream met extra laadopties

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Bestandsnaam |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Laadopties |

### Retourwaarde

Leest presentatie

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IPresentation](../../ipresentation/)
* Klasse [IPresentationFactory](../)
* Klasse [ILoadOptions](../../iloadoptions/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)