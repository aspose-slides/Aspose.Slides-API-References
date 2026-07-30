---
title: IsEmpty()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica se la stringa è vuota.
type: docs
weight: 14
url: /it/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) metodo


Verifica se la stringa è vuota.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) per verificare se è vuoto. |

### Valore di ritorno

True se la stringa è vuota (null-length), false altrimenti.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) metodo


Verifica se la collezione è vuota.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Tipo della collezione. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Collezione da verificare. |

### Valore di ritorno

True se la collezione ha un conteggio di elementi pari a zero, false altrimenti.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Struttura [TestTools](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)