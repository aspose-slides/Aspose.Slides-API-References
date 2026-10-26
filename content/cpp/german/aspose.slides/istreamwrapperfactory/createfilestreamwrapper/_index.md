---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen FileStream mit dem angegebenen Pfad und dem Erstellungsmodus.
type: docs
weight: 14
url: /de/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) Methode

Erstellt einen FileStream mit dem angegebenen Pfad und dem Erstellungsmodus.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | File name [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | File mode [System::IO::FileMode](../../../system.io/filemode/) |

### Rückgabewert

Stream wrapper for COM interface [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) Methode

Erstellt einen FileStream mit dem angegebenen Pfad, dem Erstellungsmodus und der Lese-/Schreibberechtigung.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | File name [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | File mode [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | File access [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Rückgabewert

Stream wrapper for COM interface [IStreamWrapper](../../istreamwrapper/)

## Siehe auch

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IStreamWrapper](../../istreamwrapper/)
* Klasse [String](../../../system/string/)
* Klasse [IStreamWrapperFactory](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)