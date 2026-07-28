---
title: ReadPresentation()
second_title: Aspose.Slides C++ API Referencia
description: Létező prezentációt olvas be tömbből
type: docs
weight: 27
url: /hu/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metódus


Létező prezentációt olvas be tömbből

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Olvasandó tömb |

### Visszatérési érték

Olvasott prezentáció

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metódus


Létező prezentációt olvas be tömbből további betöltési beállításokkal

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Olvasandó tömb |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Betöltési beállítások |

### Visszatérési érték

Olvasott prezentáció

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metódus


Létező prezentációt olvas be adatfolyamból

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Olvasandó bemeneti adatfolyam |

### Visszatérési érték

Olvasott prezentáció

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metódus


Létező prezentációt olvas be adatfolyamból további betöltési beállításokkal

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Olvasandó bemeneti adatfolyam |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Betöltési beállítások |

### Visszatérési érték

Olvasott prezentáció

## IPresentationFactory::ReadPresentation(System::String) metódus


Létező prezentációt olvas be fájlból

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Fájlnév |

### Visszatérési érték

Olvasott prezentáció

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metódus


Létező prezentációt olvas be adatfolyamból további betöltési beállításokkal

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Fájlnév |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Betöltési beállítások |

### Visszatérési érték

Olvasott prezentáció

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [IPresentation](../../ipresentation/)
* Osztály [IPresentationFactory](../)
* Osztály [ILoadOptions](../../iloadoptions/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)