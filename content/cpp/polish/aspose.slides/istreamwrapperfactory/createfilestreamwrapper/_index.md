---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy FileStream z określoną ścieżką i trybem tworzenia.
type: docs
weight: 14
url: /pl/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) metoda

Tworzy FileStream z określoną ścieżką i trybem tworzenia.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | File name [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | File mode [System::IO::FileMode](../../../system.io/filemode/) |

### Wartość zwracana

Wrapper strumienia dla interfejsu COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) metoda

Tworzy FileStream z określoną ścieżką, trybem tworzenia i uprawnieniami odczytu/zapisu.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | File name [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | File mode [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | File access [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Wartość zwracana

Wrapper strumienia dla interfejsu COM [IStreamWrapper](../../istreamwrapper/)

## Zobacz także

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IStreamWrapper](../../istreamwrapper/)
* Klasa [String](../../../system/string/)
* Klasa [IStreamWrapperFactory](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)