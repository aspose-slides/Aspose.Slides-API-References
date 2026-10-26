---
title: EnumerateFiles()
second_title: Referência da API Aspose.Slides para C++
description: Busca os arquivos que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado.
type: docs
weight: 40
url: /pt/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) método

Busca os arquivos que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Caminho completo ou relativo para o diretório onde pesquisar |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser realizada apenas no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado |

### Valor de Retorno

A coleção enumerável de caminhos completos dos arquivos encontrados cujos nomes correspondem a **searchPattern**

## Veja Também

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)