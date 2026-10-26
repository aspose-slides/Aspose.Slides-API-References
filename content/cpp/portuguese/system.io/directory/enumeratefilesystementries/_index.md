---
title: EnumerateFileSystemEntries()
second_title: Referência da API Aspose.Slides para C++
description: Pesquisa os arquivos e diretórios que atendem ao critério de pesquisa especificado, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado.
type: docs
weight: 53
url: /pt/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String&, const String&, SearchOption) método

Pesquisa os arquivos e diretórios que atendem ao critério de pesquisa especificado, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Caminho completo ou relativo para o diretório onde pesquisar |
| searchPattern | const [String](../../../system/string/)& | O padrão de nome dos arquivos e diretórios a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser realizada apenas no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado |

### Valor de Retorno

A coleção enumerável de caminhos completos dos arquivos e diretórios encontrados cujos nomes correspondem a **searchPattern**

## Ver Também

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Classe [String](../../../system/string/)
* Classe [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)