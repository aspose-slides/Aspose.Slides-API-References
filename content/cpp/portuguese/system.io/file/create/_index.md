---
title: Create()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo arquivo (ou sobrescreve o existente) e o abre para acesso de leitura e gravação usando o tamanho de buffer e as opções especificados.
type: docs
weight: 53
url: /pt/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) método

Cria um novo arquivo (ou sobrescreve o existente) e o abre para acesso de leitura e gravação usando o tamanho de buffer e as opções especificados.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser criado ou sobrescrito |
| bufferSize | **int32_t** | O número de bytes armazenados em buffer ao ler e gravar no arquivo |
| options | [FileOptions](../../fileoptions/) | Especifica como criar ou sobrescrever o arquivo |

### Valor de Retorno

Um ponteiro compartilhado para o objeto [FileStream](../../filestream/) associado ao arquivo especificado

## Veja Também

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)