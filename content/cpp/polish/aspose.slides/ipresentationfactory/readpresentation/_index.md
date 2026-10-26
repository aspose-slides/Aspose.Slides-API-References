---
title: ReadPresentation()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Odczytuje istniejącą prezentację z tablicy
type: docs
weight: 27
url: /pl/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metoda


Odczytuje istniejącą prezentację z tablicy

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica do odczytu |

### Wartość zwracana

Wczytana prezentacja

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metoda


Odczytuje istniejącą prezentację z tablicy z dodatkowymi opcjami ładowania

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica do odczytu |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opcje ładowania |

### Wartość zwracana

Wczytana prezentacja

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metoda


Odczytuje istniejącą prezentację ze strumienia

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy do odczytu |

### Wartość zwracana

Wczytana prezentacja

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metoda


Odczytuje istniejącą prezentację ze strumienia z dodatkowymi opcjami ładowania

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy do odczytu |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opcje ładowania |

### Wartość zwracana

Wczytana prezentacja

## IPresentationFactory::ReadPresentation(System::String) metoda


Odczytuje istniejącą prezentację z pliku

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nazwa pliku |

### Wartość zwracana

Wczytana prezentacja

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metoda


Odczytuje istniejącą prezentację z pliku z dodatkowymi opcjami ładowania

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nazwa pliku |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opcje ładowania |

### Wartość zwracana

Wczytana prezentacja

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPresentation](../../ipresentation/)
* Class [IPresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)