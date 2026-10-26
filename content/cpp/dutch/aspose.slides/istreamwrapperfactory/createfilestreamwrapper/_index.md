---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een FileStream met het opgegeven pad en aanmaakmodus.
type: docs
weight: 14
url: /nl/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) methode


Maakt een FileStream met het opgegeven pad en aanmaakmodus.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Bestandsnaam [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Bestandsmodus [System::IO::FileMode](../../../system.io/filemode/) |

### Retourwaarde

Stream wrapper voor COM-interface [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) methode


Maakt een FileStream met het opgegeven pad, aanmaakmodus en lees/schrijfrechten.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Bestandsnaam [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Bestandsmodus [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Bestandstoegang [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Retourwaarde

Stream wrapper voor COM-interface [IStreamWrapper](../../istreamwrapper/)

## Zie ook

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IStreamWrapper](../../istreamwrapper/)
* Klasse [String](../../../system/string/)
* Klasse [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)