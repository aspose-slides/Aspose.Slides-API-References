---
title: KeyValuePair()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializzatore di coppia chiave-valore nullo.
type: docs
weight: 1
url: /it/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() costruttore


Inizializzatore di coppia chiave-valore nullo.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) costruttore


Costruttore.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | const TKey\& | Chiave. |
| value | const TValue\& | Valore. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) costruttore


Costruttore di conversione di tipo.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```


### Parametri di modello

| Parametro | Descrizione |
| --- | --- |
| OtherK | Altro tipo di chiave. |
| OtherV | Altro tipo di valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | Valore della coppia. |

## Vedi anche

* Classe [KeyValuePair](../)
* Namespace [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)