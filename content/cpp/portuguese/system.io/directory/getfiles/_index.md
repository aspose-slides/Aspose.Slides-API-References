---
title: GetFiles()
second_title: Referência da API Aspose.Slides para C++
description: Procura pelos arquivos que satisfazem os critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios com raiz no diretório especificado.
type: docs
weight: 79
url: /pt/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) método


Procura pelos arquivos que satisfazem os critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios com raiz no diretório especificado.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Caminho completo ou relativo para o diretório onde procurar |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos a serem procurados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser realizada apenas no diretório especificado ou em toda a árvore de diretórios com raiz no diretório especificado |

### Valor de Retorno

Um array de caminhos completos dos arquivos encontrados cujos nomes correspondem ao **searchPattern**

## Veja Também

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)