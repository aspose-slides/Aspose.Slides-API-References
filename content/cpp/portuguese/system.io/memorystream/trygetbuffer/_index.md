---
title: TryGetBuffer()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o array de bytes sem sinal a partir do qual este fluxo foi criado.
type: docs
weight: 170
url: /pt/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) método


Retorna o array de bytes sem sinal a partir do qual este fluxo foi criado.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | array de bytes - parâmetro de saída. Quando este método retorna true, o segmento de array de bytes a partir do qual este fluxo foi criado; quando este método retorna false, este parâmetro recebe o valor padrão. |

### Valor de Retorno

True se a conversão for bem-sucedida.

## Veja Também

* Classe [ArraySegment](../../../system/arraysegment/)
* Classe [MemoryStream](../)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)