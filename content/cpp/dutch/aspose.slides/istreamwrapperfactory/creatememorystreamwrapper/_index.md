---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt een MemoryStream-wrapper.
type: docs
weight: 1
url: /nl/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() methode

Maakt een MemoryStream-wrapper.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### Retourwaarde

Stream-wrapper voor COM-interface [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) methode

Maakt een MemoryStream-wrapper op basis van de opgegeven byte-array.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-array **uint8_t**[] |

### Retourwaarde

Stream-wrapper voor COM-interface [IStreamWrapper](../../istreamwrapper/)

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IStreamWrapper](../../istreamwrapper/)
* Klasse [IStreamWrapperFactory](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)