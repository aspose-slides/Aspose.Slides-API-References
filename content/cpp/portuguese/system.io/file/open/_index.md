---
title: Open()
second_title: Referência da API Aspose.Slides para C++
description: Abre o arquivo especificado no modo especificado para leitura e escrita e sem compartilhamento.
type: docs
weight: 235
url: /pt/system.io/file/open/
---
## File::Open(const String\&, FileMode) método

Abre o arquivo especificado no modo especificado para leitura e escrita e sem compartilhamento.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser aberto |
| mode | [FileMode](../../filemode/) | Especifica o modo no qual abrir o arquivo |

### Valor de Retorno

Um objeto [FileStream](../../filestream/) associado ao arquivo aberto

## File::Open(const String\&, FileMode, FileAccess, FileShare) método

Abre o arquivo especificado no modo especificado, com o tipo de acesso especificado e opção de compartilhamento.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser aberto |
| mode | [FileMode](../../filemode/) | Especifica o modo no qual abrir o arquivo |
| access | [FileAccess](../../fileaccess/) | O tipo de acesso solicitado |
| share | [FileShare](../../fileshare/) | O tipo de acesso que outros objetos [FileStream](../../filestream/) têm ao arquivo aberto |

### Valor de Retorno

Um objeto [FileStream](../../filestream/) associado ao arquivo aberto

## Ver Também

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)