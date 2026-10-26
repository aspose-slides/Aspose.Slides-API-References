---
title: EnumerateDirectories()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma coleção enumerável contendo todos os diretórios localizados no diretório representado pelo objeto atual.
type: docs
weight: 105
url: /pt/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() método


Retorna uma coleção enumerável contendo todos os diretórios localizados no diretório representado pelo objeto atual.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) método


Pesquisa os diretórios que atendem ao critério de busca especificado no diretório representado pelo objeto atual.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos diretórios a serem pesquisados |

### Valor de Retorno

A coleção enumerável de ponteiros compartilhados para objetos [DirectoryInfo](../) que representam os diretórios encontrados cujos nomes correspondem a **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) método


Pesquisa os diretórios que atendem ao critério de busca especificado tanto no diretório representado pelo objeto atual quanto em toda a árvore de diretórios enraizada no diretório representado pelo objeto atual.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos diretórios a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a busca deve ser realizada apenas no diretório representado pelo objeto atual ou em toda a árvore de diretórios enraizada no diretório representado pelo objeto atual |

### Valor de Retorno

A coleção enumerável de ponteiros compartilhados para objetos [DirectoryInfo](../) que representam os diretórios encontrados cujos nomes correspondem a **searchPattern**

## Veja Também

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)