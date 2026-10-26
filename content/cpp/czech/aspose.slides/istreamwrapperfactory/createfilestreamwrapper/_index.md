---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří FileStream se zadanou cestou a režimem vytváření.
type: docs
weight: 14
url: /cs/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) metoda


Vytvoří FileStream se zadanou cestou a režimem vytváření.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Název souboru [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Režim souboru [System::IO::FileMode](../../../system.io/filemode/) |

### Návratová hodnota

Obal proudu pro rozhraní COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) metoda


Vytvoří FileStream se zadanou cestou, režimem vytvoření a oprávněním pro čtení/zápis.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Název souboru [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Režim souboru [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Přístup k souboru [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Návratová hodnota

Obal proudu pro rozhraní COM [IStreamWrapper](../../istreamwrapper/)

## Viz také

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [String](../../../system/string/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)