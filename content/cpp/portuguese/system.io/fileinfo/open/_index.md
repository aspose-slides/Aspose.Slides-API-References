---
title: Open()
second_title: Referência da API Aspose.Slides para C++
description: Abre o arquivo representado pelo objeto atual no modo especificado para leitura e gravação e sem compartilhamento.
type: docs
weight: 183
url: /pt/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) método


Abre o arquivo representado pelo objeto atual no modo especificado para leitura e gravação e sem compartilhamento.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Especifica o modo no qual abrir o flie |

### Valor de Retorno

Um objeto [FileStream](../../filestream/) associado ao arquivo representado pelo objeto atual

## FileInfo::Open(FileMode, FileAccess) método


Abre o arquivo representado pelo objeto atual no modo especificado, com o tipo de acesso especificado e sem compartilhamento.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Especifica o modo no qual abrir o flie |
| access | [FileAccess](../../fileaccess/) | O tipo de acesso solicitado |

### Valor de Retorno

Um objeto [FileStream](../../filestream/) associado ao arquivo representado pelo objeto atual

## FileInfo::Open(FileMode, FileAccess, FileShare) método


Abre o arquivo representado pelo objeto atual no modo especificado, com o tipo de acesso especificado e opção de compartilhamento.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Especifica o modo no qual abrir o flie |
| access | [FileAccess](../../fileaccess/) | O tipo de acesso solicitado |
| share | [FileShare](../../fileshare/) | O tipo de acesso que outros objetos [FileStream](../../filestream/) têm ao arquivo aberto |

### Valor de Retorno

Um objeto [FileStream](../../filestream/) associado ao arquivo representado pelo objeto atual

## Veja Também

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)