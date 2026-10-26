---
title: Copy()
second_title: Referência da API Aspose.Slides para C++
description: Copia o arquivo especificado para o local especificado. Se o arquivo de destino já existir, um parâmetro especifica se ele deve ser sobrescrito.
type: docs
weight: 40
url: /pt/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) method

Copia o arquivo especificado para o local especificado. Se o arquivo de destino já existir, um parâmetro especifica se ele deve ser sobrescrito.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Um caminho do arquivo a ser copiado |
| destFileName | const [String](../../../system/string/)\& | Um caminho do novo local do arquivo a ser copiado |
| overwrite | **bool** | True se o arquivo de destino existente deve ser sobrescrito, false se a cópia deve falhar caso o arquivo de destino já exista |

## Ver Também

* Classe [String](../../../system/string/)
* Classe [File](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)