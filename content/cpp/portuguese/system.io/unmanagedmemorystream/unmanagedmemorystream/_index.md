---
title: UnmanagedMemoryStream()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância de UnmanagedMemoryStream.
type: docs
weight: 118
url: /pt/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) constructor


Constrói uma nova instância de [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pointer | **uint8_t** * | Um ponteiro para o buffer não gerenciado |
| length | **int64_t** | O tamanho do buffer não gerenciado em bytes |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) constructor


Constrói uma nova instância de [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pointer | **uint8_t** * | Um ponteiro para o buffer não gerenciado |
| length | **int64_t** | O tamanho do buffer não gerenciado em bytes |
| capacity | **int64_t** | A quantidade total de memória atribuída ao fluxo |
| access | [FileAccess](../../fileaccess/) | Especifica se o fluxo deve ser somente leitura, somente gravação ou ambos |

## Veja Também

* Enumeração [FileAccess](../../fileaccess/)
* Classe [UnmanagedMemoryStream](../)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)