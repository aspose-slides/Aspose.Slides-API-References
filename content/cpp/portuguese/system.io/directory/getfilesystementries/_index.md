---
title: GetFileSystemEntries()
second_title: Referência da API Aspose.Slides for C++
description: Pesquisa os arquivos e diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios com raiz no diretório especificado.
type: docs
weight: 92
url: /pt/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) método


Pesquisa os arquivos e diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios com raiz no diretório especificado.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Caminho completo ou relativo para o diretório onde pesquisar |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos e diretórios a serem pesquisados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a pesquisa deve ser realizada apenas no diretório especificado ou em toda a árvore de diretórios com raiz no diretório especificado |

### Valor de Retorno

Um vetor de caminhos completos dos arquivos e diretórios encontrados cujos nomes correspondem a **searchPattern**

## Veja Também

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [Directory](../)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)