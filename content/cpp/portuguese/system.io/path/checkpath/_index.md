---
title: CheckPath()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o caminho especificado é válido verificando se contém caracteres inválidos. Uma exceção é lançada se o caminho contiver caracteres inválidos.
type: docs
weight: 209
url: /pt/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) método


Determina se o caminho especificado é válido verificando se contém caracteres inválidos. Uma exceção é lançada se o caminho contiver caracteres inválidos.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho a ser verificado |
| msg | const [String](../../../system/string/)\& | A mensagem a ser passada ao construtor do objeto de exceção |
| allow_empty | **bool** | Especifica se uma string vazia ou nula deve ser considerada um caminho correto (true) ou não (false); se este parâmetro for false e **path** estiver vazio, uma ArgumentException será lançada; se este parâmetro for false e **path** for nulo, uma ArgumentNullException será lançada |

## Veja também

* Classe [String](../../../system/string/)
* Classe [Path](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)