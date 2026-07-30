---
title: UnmanagedMemoryStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza di UnmanagedMemoryStream.
type: docs
weight: 118
url: /it/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) costruttore


Crea una nuova istanza di [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pointer | **uint8_t** * | Un puntatore a buffer non gestito |
| length | **int64_t** | La dimensione del buffer non gestito in byte |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) costruttore


Crea una nuova istanza di [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pointer | **uint8_t** * | Un puntatore a buffer non gestito |
| length | **int64_t** | La dimensione del buffer non gestito in byte |
| capacity | **int64_t** | La quantità totale di memoria assegnata al flusso |
| access | [FileAccess](../../fileaccess/) | Specifica se il flusso deve essere solo lettura, solo scrittura o entrambi |

## Vedi anche

* Enum [FileAccess](../../fileaccess/)
* Classe [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)