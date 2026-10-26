---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides C++ API referencia
description: MemoryStream csomagolót hoz létre.
type: docs
weight: 1
url: /hu/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() method


MemoryStream csomagolót hoz létre.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```


### Visszatérési érték

Stream csomagoló a COM interfészhez [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) method


Megadott byte tömb alapján MemoryStream csomagolót hoz létre.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte tömb **uint8_t**[] |

### Visszatérési érték

Stream csomagoló a COM interfészhez [IStreamWrapper](../../istreamwrapper/)

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)