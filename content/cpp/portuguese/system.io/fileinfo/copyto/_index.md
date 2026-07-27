---
title: CopyTo()
second_title: Referência da API Aspose.Slides para C++
description: Copia o arquivo representado pelo objeto atual para o local especificado. Se o arquivo de destino já existir, a cópia falha.
type: docs
weight: 105
url: /pt/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) método

Copia o arquivo representado pelo objeto atual para o local especificado. Se o arquivo de destino já existir, a cópia falhará.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | O nome do arquivo de destino |

### Valor de Retorno

Um objeto [FileInfo](../) que representa a cópia

## FileInfo::CopyTo(const String\&, bool) método

Copia o arquivo representado pelo objeto atual para o local especificado. Um parâmetro indica se o arquivo de destino existente deve ser sobrescrito.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | O nome do arquivo de destino |
| overwrite | **bool** | True se o arquivo de destino existente deve ser sobrescrito, false se a cópia deve falhar se o arquivo de destino já existir |

### Valor de Retorno

Um objeto [FileInfo](../) que representa a cópia

## Veja Também

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Classe [String](../../../system/string/)
* Classe [FileInfo](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)