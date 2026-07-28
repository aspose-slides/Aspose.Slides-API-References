---
title: ReadPresentation()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Odczytuje istniejącą prezentację z tablicy
type: docs
weight: 40
url: /pl/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metoda


Odczytuje istniejącą prezentację z tablicy

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica do odczytu |

### Wartość zwracana

Odczytana prezentacja

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metoda


Odczytuje istniejącą prezentację z tablicy z dodatkowymi opcjami ładowania

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica do odczytu |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opcje ładowania |

### Wartość zwracana

Odczytana prezentacja

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metoda


Odczytuje istniejącą prezentację ze strumienia

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy do odczytu |

### Wartość zwracana

Odczytana prezentacja

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metoda


Odczytuje istniejącą prezentację ze strumienia z dodatkowymi opcjami ładowania

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy do odczytu |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opcje ładowania |

### Wartość zwracana

Odczytana prezentacja

## PresentationFactory::ReadPresentation(System::String) metoda


Odczytuje istniejącą prezentację z pliku

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nazwa pliku |

### Wartość zwracana

Odczytana prezentacja

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metoda


Odczytuje istniejącą prezentację z pliku z dodatkowymi opcjami ładowania

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nazwa pliku |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opcje ładowania |

### Wartość zwracana

Odczytana prezentacja

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [IPresentation](../../ipresentation/)
* Klasa [PresentationFactory](../)
* Klasa [ILoadOptions](../../iloadoptions/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)