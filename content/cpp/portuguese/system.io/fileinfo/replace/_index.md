---
title: Replace()
second_title: Referência da API Aspose.Slides para C++
description: Substitui o conteúdo de um arquivo de destino especificado pelo arquivo representado pelo objeto FileInfo atual e cria uma cópia de segurança do arquivo substituído.
type: docs
weight: 131
url: /pt/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) método


Substitui o conteúdo de um arquivo de destino especificado pelo arquivo representado pelo objeto [FileInfo](../) atual e cria uma cópia de segurança do arquivo substituído.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Um nome do arquivo a ser substituído |
| destinationBackupFileName | const [String](../../../system/string/)\& | Um nome do arquivo de backup |

### Valor de Retorno

Um objeto FileInfor que representa o arquivo apontado por **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) método


Substitui o conteúdo de um arquivo de destino especificado pelo arquivo representado pelo objeto [FileInfo](../) atual e cria uma cópia de segurança do arquivo substituído.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Um nome do arquivo a ser substituído |
| destinationBackupFileName | const [String](../../../system/string/)\& | Um nome do arquivo de backup |
| ignoreMetadataErrors | **bool** | Especifica se os erros de mesclagem do arquivo substituído para o arquivo de substituição devem ser ignorados (true) ou não (false) |

### Valor de Retorno

Um objeto FileInfor que representa o arquivo apontado por **destinationFileName**

## Veja Também

* Tipo [FileInfoPtr](../../../system/fileinfoptr/)
* Classe [String](../../../system/string/)
* Classe [FileInfo](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)