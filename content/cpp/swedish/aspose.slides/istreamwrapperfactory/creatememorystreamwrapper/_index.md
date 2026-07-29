---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides för C++ API-referens
description: Skapar MemoryStream wrapper.
type: docs
weight: 1
url: /sv/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() metod


Skapar MemoryStream wrapper.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```


### Returvärde

Strömwrapper för COM-gränssnitt [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) metod


Skapar MemoryStream wrapper baserat på den specificerade bytearrayen.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-array **uint8_t**[] |

### Returvärde

Strömwrapper för COM-gränssnitt [IStreamWrapper](../../istreamwrapper/)

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IStreamWrapper](../../istreamwrapper/)
* Klass [IStreamWrapperFactory](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)