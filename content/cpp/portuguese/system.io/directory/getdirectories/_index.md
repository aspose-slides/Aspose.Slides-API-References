---
title: GetDirectories()
second_title: Referência da API Aspose.Slides para C++
description: Procura os diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado.
type: docs
weight: 66
url: /pt/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) método

Procura os diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Caminho completo ou relativo para o diretório onde pesquisar |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos diretórios a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser realizada apenas no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado |

### Valor de retorno

Um array de caminhos completos dos diretórios encontrados cujos nomes correspondem ao **searchPattern**

## Veja também

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)