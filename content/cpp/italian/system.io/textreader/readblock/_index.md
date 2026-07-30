---
title: ReadBlock()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il numero massimo specificato di caratteri dal lettore di testo corrente e scrive i dati in un buffer, iniziando dall'indice specificato.
type: docs
weight: 53
url: /it/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) method


Legge il numero massimo specificato di caratteri dal lettore di testo corrente e scrive i dati in un buffer, iniziando dall'indice specificato.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Un buffer di caratteri per scrivere i dati letti |
| index | int | Un indice a base 0 in **buffer** da cui iniziare a scrivere |
| count | int | Il numero massimo di caratteri da leggere |

### Valore di ritorno

Il numero effettivo di caratteri letti

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [TextReader](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)