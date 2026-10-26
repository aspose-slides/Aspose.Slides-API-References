---
title: Replace()
second_title: Referência da API Aspose.Slides para C++
description: Substitui o conteúdo de um arquivo por outro e cria um backup do arquivo substituído.
type: docs
weight: 339
url: /pt/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) método

Substitui o conteúdo de um arquivo por outro e cria um backup do arquivo substituído.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Um nome do arquivo para substituir |
| destinationFileName | const [String](../../../system/string/)\& | Um nome do arquivo a ser substituído |
| destinationBackupFileName | const [String](../../../system/string/)\& | Um nome do arquivo de backup |
| ignoreMetadataErrors | **bool** | Especifica se os erros de mesclagem do arquivo substituído para o arquivo de substituição devem ser ignorados (true) ou não (false) |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [File](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)