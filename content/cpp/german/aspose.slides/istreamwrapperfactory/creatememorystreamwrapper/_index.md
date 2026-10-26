---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen MemoryStream-Wrapper.
type: docs
weight: 1
url: /de/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() Methode

Erstellt einen MemoryStream-Wrapper.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### Rückgabewert

Stream-Wrapper für COM-Schnittstelle [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) Methode

Erstellt einen MemoryStream-Wrapper basierend auf dem angegebenen Byte-Array.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-Array **uint8_t**[] |

### Rückgabewert

Stream-Wrapper für COM-Schnittstelle [IStreamWrapper](../../istreamwrapper/)

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IStreamWrapper](../../istreamwrapper/)
* Klasse [IStreamWrapperFactory](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)