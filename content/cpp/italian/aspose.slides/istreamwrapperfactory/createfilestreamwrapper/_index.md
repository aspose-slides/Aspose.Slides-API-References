---
title: CreateFileStreamWrapper()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un FileStream con il percorso specificato e la modalità di creazione.
type: docs
weight: 14
url: /it/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) metodo


Crea un FileStream con il percorso specificato e la modalità di creazione.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nome file [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Modalità file [System::IO::FileMode](../../../system.io/filemode/) |

### Valore di ritorno

Wrapper di flusso per l'interfaccia COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) metodo


Crea un FileStream con il percorso specificato, la modalità di creazione e il permesso di lettura/scrittura.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nome file [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Modalità file [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Accesso file [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Valore di ritorno

Wrapper di flusso per l'interfaccia COM [IStreamWrapper](../../istreamwrapper/)

## Vedi anche

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IStreamWrapper](../../istreamwrapper/)
* Classe [String](../../../system/string/)
* Classe [IStreamWrapperFactory](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)