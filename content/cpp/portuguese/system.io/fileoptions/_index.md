---
title: FileOptions
second_title: Referência da API Aspose.Slides para C++
description: Representa opções avançadas para criar o objeto FileStream.
type: docs
weight: 521
url: /pt/system.io/fileoptions/
---
## FileOptions enum

Representa opções avançadas para criar o objeto [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Nenhuma opção adicional. |
| Encrypted | 16384 | O arquivo está criptografado. NÃO IMPLEMENTADO. |
| DeleteOnClose | 67108864 | O arquivo deve ser excluído automaticamente quando não estiver mais em uso. |
| SequentialScan | 134217728 | O arquivo deve ser acessado sequencialmente. |
| RandomAccess | 268435456 | O arquivo é acessado aleatoriamente. |
| Asynchronous | 1073741824 | O arquivo pode ser usado para operações de E/S assíncronas. |
| WriteThrough | n/a | Todas as gravações devem ir diretamente ao disco, ignorando qualquer cache intermediário. |

## Veja também

* Espaço de nomes [System::IO](../)
* Biblioteca [Aspose.Slides](../../)