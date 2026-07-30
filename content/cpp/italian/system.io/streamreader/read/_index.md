---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge un singolo carattere dallo stream.
type: docs
weight: 40
url: /it/system.io/streamreader/read/
---
## StreamReader::Read() metodo

Legge un singolo carattere dallo stream.

```cpp
virtual int System::IO::StreamReader::Read() override
```

### Valore di ritorno

Restituisce il carattere codificato con codifica UTF-16; se il carattere letto è rappresentato da due punti di codice nella codifica UTF-16, viene restituita solo la surragate alta.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) metodo

Legge il numero specificato di caratteri dallo stream, li converte nella codifica UTF-16 e scrive i caratteri UTF-16 risultanti nell'array di caratteri specificato a partire dalla posizione specificata.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | L'array di caratteri UTF-16 in cui scrivere i caratteri letti dallo stream |
| index | int | Un indice basato su 0 in **buffer** da cui iniziare a scrivere |
| count | int | Il numero di caratteri da leggere dallo stream |

### Valore di ritorno

Il numero di caratteri letti dallo stream

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StreamReader](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)