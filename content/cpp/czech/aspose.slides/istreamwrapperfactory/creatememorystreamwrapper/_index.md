---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides pro C++ API - reference
description: Vytváří obal MemoryStream.
type: docs
weight: 1
url: /cs/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() metoda

Vytvoří obal MemoryStream.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### Návratová hodnota

Obal streamu pro COM rozhraní [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) metoda

Vytvoří obal MemoryStream na základě zadaného pole bajtů.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů **uint8_t**[] |

### Návratová hodnota

Obal streamu pro COM rozhraní [IStreamWrapper](../../istreamwrapper/)

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IStreamWrapper](../../istreamwrapper/)
* Třída [IStreamWrapperFactory](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)