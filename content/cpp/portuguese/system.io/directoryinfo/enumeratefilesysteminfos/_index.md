---
title: EnumerateFileSystemInfos()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma coleção enumerável contendo todos os arquivos e diretórios localizados no diretório representado pelo objeto atual.
type: docs
weight: 131
url: /pt/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() método

Retorna uma coleção enumerável contendo todos os arquivos e diretórios localizados no diretório representado pelo objeto atual.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) método

Busca os arquivos e diretórios que satisfaçam os critérios de pesquisa especificados no diretório representado pelo objeto atual.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos e diretórios a serem pesquisados |

### Valor de Retorno

A coleção enumerável de ponteiros compartilhados para objetos [FileSystemInfo](../../filesysteminfo/) que representam os arquivos e diretórios encontrados cujos nomes correspondem a **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) método

Busca os arquivos e diretórios que satisfaçam os critérios de pesquisa especificados, seja no diretório representado pelo objeto atual ou em toda a árvore de diretórios enraizada no diretório representado pelo objeto atual.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos e diretórios a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser realizada apenas no diretório representado pelo objeto atual ou em toda a árvore de diretórios enraizada no diretório representado pelo objeto atual |

### Valor de Retorno

A coleção enumerável de ponteiros compartilhados para objetos [FileSystemInfo](../../filesysteminfo/) que representam os arquivos e diretórios encontrados cujos nomes correspondem a **searchPattern**

## Veja Também

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)