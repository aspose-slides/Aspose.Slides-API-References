---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge un singolo carattere dal flusso.
type: docs
weight: 40
url: /it/system.io/stringreader/read/
---
## StringReader::Read() metodo

Legge un singolo carattere dal flusso.

```cpp
virtual int System::IO::StringReader::Read() override
```

### Valore di ritorno

Un carattere letto o -1 se nessun carattere è stato letto

## StringReader::Read(ArrayPtr\<char_t\>, int, int) metodo

Legge il numero specificato di caratteri dal flusso nell'array di caratteri specificato a partire dalla posizione specificata.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | L'array di caratteri in cui scrivere i caratteri letti dal flusso |
| index | int | Un indice basato su 0 in **buffer** a partire dal quale iniziare a scrivere |
| count | int | Il numero di caratteri da leggere dal flusso |

### Valore di ritorno

Il numero di caratteri letti dal flusso

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StringReader](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)