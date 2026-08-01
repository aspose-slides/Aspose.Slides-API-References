---
title: ReadPresentation()
second_title: Aspose.Slides voor C++ API Referentie
description: Leest een bestaande presentatie uit een array
type: docs
weight: 40
url: /nl/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) methode


Leest een bestaande presentatie uit een array

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array om te lezen |

### Retourwaarde

Presentatie lezen

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) methode


Leest een bestaande presentatie uit een array met aanvullende laadopties

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array om te lezen |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Laadopties |

### Retourwaarde

Presentatie lezen

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) methode


Leest een bestaande presentatie uit een stream

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Invoerstroom om te lezen |

### Retourwaarde

Presentatie lezen

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) methode


Leest een bestaande presentatie uit een stream met aanvullende laadopties

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Invoerstroom om te lezen |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Laadopties |

### Retourwaarde

Presentatie lezen

## PresentationFactory::ReadPresentation(System::String) methode


Leest een bestaande presentatie uit een bestand

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Bestandsnaam |

### Retourwaarde

Presentatie lezen

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) methode


Leest een bestaande presentatie uit een stream met aanvullende laadopties

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Bestandsnaam |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Laadopties |

### Retourwaarde

Presentatie lezen

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IPresentation](../../ipresentation/)
* Klasse [PresentationFactory](../)
* Klasse [ILoadOptions](../../iloadoptions/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)