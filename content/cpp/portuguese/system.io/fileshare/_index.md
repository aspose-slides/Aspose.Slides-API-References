---
title: FileShare
second_title: Referência da API Aspose.Slides para C++
description: Especifica que tipo de acesso outros objetos FileStream podem ter a um arquivo que está sendo aberto.
type: docs
weight: 534
url: /pt/system.io/fileshare/
---
## FileShare enum

Especifica que tipo de acesso outros objetos [FileStream](../filestream/) podem ter a um arquivo que está sendo aberto.

```cpp
enum class FileShare
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Sem acesso. |
| Read | 1 | Acesso somente leitura. |
| Write | 2 | Acesso somente gravação. |
| ReadWrite | 3 | Acesso de leitura e gravação. |
| Delete | 4 | O arquivo pode ser excluído. |
| Inheritable | 16 | Torna o manipulador de arquivo herdável por processos filhos. |

## Veja Também

* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)