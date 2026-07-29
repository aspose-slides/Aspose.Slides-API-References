---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides för C++ API-referens
description: Skapar FileStream med den angivna sökvägen och skapningsläget.
type: docs
weight: 14
url: /sv/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) metod


Skapar FileStream med den angivna sökvägen och skapningsläget.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Filnamn [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Filläge [System::IO::FileMode](../../../system.io/filemode/) |

### Returvärde

Strömwrapper för COM-gränssnitt [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) metod


Skapar FileStream med den angivna sökvägen, skapningsläget och läs/skriv-behörighet.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Filnamn [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Filläge [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Filåtkomst [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Returvärde

Strömwrapper för COM-gränssnitt [IStreamWrapper](../../istreamwrapper/)

## Se även

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IStreamWrapper](../../istreamwrapper/)
* klass [String](../../../system/string/)
* klass [IStreamWrapperFactory](../)
* namnrymd [Aspose::Slides](../../)
* bibliotek [Aspose.Slides](../../../)