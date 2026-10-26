---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehozza a FileStream-et a megadott úttal és létrehozási móddal.
type: docs
weight: 14
url: /hu/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) metódus

Létrehozza a FileStream-et a megadott úttal és létrehozási móddal.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Fájlnév [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Fájl mód [System::IO::FileMode](../../../system.io/filemode/) |

### Visszatérési érték

Stream wrapper a COM interfészhez [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) metódus

Létrehozza a FileStream-et a megadott úttal, létrehozási móddal és olvasási/írási jogosultsággal.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Fájlnév [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Fájl mód [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Fájl hozzáférés [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Visszatérési érték

Stream wrapper a COM interfészhez [IStreamWrapper](../../istreamwrapper/)

## Lásd még

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [String](../../../system/string/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)