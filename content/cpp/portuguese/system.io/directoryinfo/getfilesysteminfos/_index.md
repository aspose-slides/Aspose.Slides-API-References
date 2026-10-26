---
title: GetFileSystemInfos()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um array contendo ponteiros compartilhados para objetos FileSystemInfo que representam todos os arquivos e diretórios localizados no diretório representado pelo objeto atual.
type: docs
weight: 170
url: /pt/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() método

Retorna um array contendo ponteiros compartilhados para objetos [FileSystemInfo](../../filesysteminfo/) que representam todos os arquivos e diretórios localizados no diretório representado pelo objeto atual.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) método

Procura pelos arquivos e diretórios que atendem ao critério de pesquisa especificado no diretório representado pelo objeto atual.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos e diretórios a serem pesquisados |

### Valor de Retorno

Um array de ponteiros compartilhados para objetos [FileSystemInfo](../../filesysteminfo/) que representam os arquivos e diretórios encontrados cujos nomes correspondem a **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) método

Procura pelos arquivos e diretórios que atendem ao critério de pesquisa especificado, seja no diretório representado pelo objeto atual ou em toda a árvore de diretórios com raiz no diretório representado pelo objeto atual.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos e diretórios a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser executada apenas no diretório representado pelo objeto atual ou em toda a árvore de diretórios com raiz no diretório representado pelo objeto atual |

### Valor de Retorno

Um array de ponteiros compartilhados para objetos [FileSystemInfo](../../filesysteminfo/) que representam os arquivos e diretórios encontrados cujos nomes correspondem a **searchPattern**

## Ver Também

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* classe [DirectoryInfo](../)
* classe [String](../../../system/string/)
* namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)