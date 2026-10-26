---
title: ReadPresentation()
second_title: Aspose.Slides C++ API Referenciája
description: Beolvas egy meglévő prezentációt tömbből
type: docs
weight: 40
url: /hu/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metódus

Beolvas egy meglévő prezentációt tömbből

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Beolvasandó tömb |

### Visszatérési érték

Beolvasott prezentáció

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metódus

Beolvas egy meglévő prezentációt tömbből további betöltési beállításokkal

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Beolvasandó tömb |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Betöltési beállítások |

### Visszatérési érték

Beolvasott prezentáció

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metódus

Beolvas egy meglévő prezentációt adatfolyamból

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Beolvasandó bemeneti adatfolyam |

### Visszatérési érték

Beolvasott prezentáció

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metódus

Beolvas egy meglévő prezentációt adatfolyamból további betöltési beállításokkal

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Beolvasandó bemeneti adatfolyam |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Betöltési beállítások |

### Visszatérési érték

Beolvasott prezentáció

## PresentationFactory::ReadPresentation(System::String) metódus

Beolvas egy meglévő prezentációt fájlból

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Fájl neve |

### Visszatérési érték

Beolvasott prezentáció

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metódus

Beolvas egy meglévő prezentációt fájlból további betöltési beállításokkal

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Fájl neve |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Betöltési beállítások |

### Visszatérési érték

Beolvasott prezentáció

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [IPresentation](../../ipresentation/)
* Osztály [PresentationFactory](../)
* Osztály [ILoadOptions](../../iloadoptions/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)