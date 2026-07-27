---
title: EnumerateFiles()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma coleção enumerável contendo todos os arquivos localizados no diretório representado pelo objeto atual.
type: docs
weight: 118
url: /pt/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() método

Retorna uma coleção enumerável contendo todos os arquivos localizados no diretório representado pelo objeto atual.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) método

Procura os arquivos que atendem ao critério de pesquisa especificado no diretório representado pelo objeto atual.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos a serem pesquisados |

### Valor de Retorno

A coleção enumerável de ponteiros compartilhados para objetos [FileInfo](../../fileinfo/) que representam os arquivos encontrados cujos nomes correspondem a **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) método

Procura os arquivos que atendem ao critério de pesquisa especificado ou no diretório representado pelo objeto atual ou em toda a árvore de diretórios cujo raiz é o diretório representado pelo objeto atual.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser realizada apenas no diretório representado pelo objeto atual ou em toda a árvore de diretórios cuja raiz é o diretório representado pelo objeto atual |

### Valor de Retorno

A coleção enumerável de ponteiros compartilhados para objetos [FileInfo](../../fileinfo/) que representam os arquivos encontrados cujos nomes correspondem a **searchPattern**

## Veja Também

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [DirectoryInfo](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)