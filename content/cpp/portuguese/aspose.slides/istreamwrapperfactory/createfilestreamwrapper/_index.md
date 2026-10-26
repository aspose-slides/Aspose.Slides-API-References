---
title: CreateFileStreamWrapper()
second_title: Referência da API Aspose.Slides para C++
description: Cria FileStream com o caminho especificado e o modo de criação.
type: docs
weight: 14
url: /pt/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) método

Cria FileStream com o caminho especificado e o modo de criação.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nome do arquivo [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Modo de arquivo [System::IO::FileMode](../../../system.io/filemode/) |

### Return Value

Wrapper de fluxo para a interface COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) método

Cria FileStream com o caminho especificado, modo de criação e permissão de leitura/gravação.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nome do arquivo [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Modo de arquivo [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Acesso ao arquivo [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Return Value

Wrapper de fluxo para a interface COM [IStreamWrapper](../../istreamwrapper/)

## Veja Também

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IStreamWrapper](../../istreamwrapper/)
* Classe [String](../../../system/string/)
* Classe [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)