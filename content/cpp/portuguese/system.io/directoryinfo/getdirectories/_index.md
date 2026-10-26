---
title: GetDirectories()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma matriz contendo ponteiros compartilhados para objetos DirectoryInfo que representam todos os diretórios localizados no diretório representado pelo objeto atual.
type: docs
weight: 144
url: /pt/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() método


Retorna uma matriz contendo ponteiros compartilhados para objetos [DirectoryInfo](../) que representam todos os diretórios localizados no diretório representado pelo objeto atual.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) método


Procura os diretórios que atendem ao critério de pesquisa especificado no diretório representado pelo objeto atual.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos diretórios a serem pesquisados |

### Valor de Retorno

Uma matriz de ponteiros compartilhados para objetos [DirectoryInfo](../) que representam os diretórios encontrados cujos nomes correspondem a **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) método


Procura os diretórios que atendem ao critério de pesquisa especificado, seja no diretório representado pelo objeto atual, seja em toda a árvore de diretórios enraizada no diretório representado pelo objeto atual.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos diretórios a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser realizada apenas no diretório representado pelo objeto atual ou em toda a árvore de diretórios enraizada no diretório representado pelo objeto atual |

### Valor de Retorno

Uma matriz de ponteiros compartilhados para objetos [DirectoryInfo](../) que representam os diretórios encontrados cujos nomes correspondem a **searchPattern**

## Veja Também

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)