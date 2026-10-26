---
title: MemoryStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza della classe MemoryStream con capacità iniziale pari a 0.
type: docs
weight: 1
url: /it/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() costruttore

Crea una nuova istanza della classe [MemoryStream](../) con capacità iniziale pari a 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) costruttore

Crea una nuova istanza della classe [MemoryStream](../) che rappresenta un flusso basato su un buffer di memoria della dimensione specificata.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| capacity_ | int | La dimensione in byte di un buffer di memoria associato al flusso rappresentato dall'oggetto in fase di creazione |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) costruttore

Crea una nuova istanza della classe [MemoryStream](../) che rappresenta un flusso di memoria collegato al buffer di memoria specificato. Un parametro indica se il flusso è scrivibile.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un array di byte da utilizzare come buffer di memoria su cui sarà basato il flusso rappresentato dall'oggetto in fase di creazione |
| writable | **bool** | Indica se il flusso deve essere scrivibile |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) costruttore

Crea una nuova istanza della classe [MemoryStream](../) che rappresenta un flusso di memoria collegato a un segmento del buffer di memoria specificato, a partire dall'indice specificato e comprendente il numero specificato di elementi. I parametri indicano se il flusso è scrivibile e se il metodo GetBytes() può essere chiamato.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un array di byte di cui un segmento sarà utilizzato come buffer di memoria su cui sarà basato il flusso rappresentato dall'oggetto in fase di creazione |
| index | int | Un indice a base 0 dell'elemento in **content** al quale inizia il segmento |
| count | int | Il numero di elementi di **content** inclusi nel segmento |
| writable | **bool** | Indica se il flusso deve essere scrivibile |
| publiclyVisible | **bool** | Specifica se il buffer di memoria sottostante deve essere reso disponibile al chiamante del metodo GetByte() |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)