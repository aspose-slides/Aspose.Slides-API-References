---
title: BitVector32
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce un semplice vettore di bit leggero con facile accesso intero o Booleano a una memoria da 32 bit.
type: docs
weight: 1
url: /it/system.collections.specialized/bitvector32/
---
## BitVector32 classe

Fornisce un semplice vettore di bit leggero con facile accesso intero o [Boolean](../../system/boolean/) a una memoria da 32 bit.

```cpp
class BitVector32
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Inizializza una nuova istanza vuota di [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Inizializza una nuova istanza della struttura [BitVector32](./) con i dati interni specificati. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Inizializza una nuova istanza della struttura [BitVector32](./) con le informazioni nel valore specificato. |
| static **int32_t** [CreateMask](./createmask/)() | Crea la prima maschera in una serie. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Crea la prossima maschera in una serie. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Crea la prima sezione in una serie, con il valore massimo specificato. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Crea la prossima sezione in una serie, con il valore massimo specificato. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Determina se l'oggetto specificato è lo stesso di quello corrente. |
| **int32_t** [get_Data](./get_data/)() | restituisce i dati grezzi memorizzati in questo vettore di bit... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Ottiene un valore che indica se tutti i bit specificati sono impostati. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Ottiene il valore per la sezione specificata. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Imposta un valore che indica se tutti i bit specificati sono impostati. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Imposta il valore per la sezione specificata. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Converte il valore rappresentato dal parametro value in stringa. |
| [String](../../system/string/) [ToString](./tostring/)() const | Converte il valore rappresentato dall'oggetto corrente in stringa. |
## Vedi anche

* Spazio dei nomi [System::Collections::Specialized](../)
* Library [Aspose.Slides](../../)