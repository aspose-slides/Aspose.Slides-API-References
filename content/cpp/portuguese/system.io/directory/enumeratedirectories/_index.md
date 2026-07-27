---
title: EnumerateDirectories()
second_title: Referência da API Aspose.Slides para C++
description: Procura pelos diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado.
type: docs
weight: 27
url: /pt/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) método

Procura pelos diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Caminho completo ou relativo para o diretório onde será feita a pesquisa |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos diretórios a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser realizada apenas no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado |

### Valor de Retorno

A coleção enumerável de caminhos completos dos diretórios encontrados cujos nomes correspondem ao **searchPattern**

## Veja também

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)