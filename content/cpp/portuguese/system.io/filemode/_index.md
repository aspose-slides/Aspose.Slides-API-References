---
title: FileMode
second_title: Referência da API Aspose.Slides para C++
description: Especifica como um arquivo deve ser aberto.
type: docs
weight: 508
url: /pt/system.io/filemode/
---
## FileMode enum

Especifica como um arquivo deve ser aberto.

```cpp
enum class FileMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| CreateNew | 1 | Cria um novo arquivo. Se o arquivo já existir, uma exceção é lançada. |
| Create | 2 | Cria um novo arquivo. Se o arquivo já existir, ele é sobrescrito. |
| Open | 3 | Abre um arquivo existente. Se o arquivo não existir, uma exceção é lançada. |
| OpenOrCreate | 4 | Abre um arquivo existente ou cria um novo se ele não existir. |
| Truncate | 5 | Abre um arquivo existente e o trunca para que fique vazio. Se o arquivo não existir, uma exceção é lançada. |
| Append | 6 | Abre um arquivo existente e posiciona no final dele ou cria um novo se ele não existir. |

## Veja Também

* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)