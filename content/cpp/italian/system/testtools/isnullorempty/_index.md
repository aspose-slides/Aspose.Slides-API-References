---
title: IsNullOrEmpty()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se la collezione è nulla o vuota.
type: docs
weight: 27
url: /it/system/testtools/isnullorempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) method


Verifica se la collezione è nulla o vuota.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di collezione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Collezione da verificare. |

### Valore di ritorno

True se la collezione è nulla o ha un conteggio di elementi pari a zero, false altrimenti.

## TestTools::IsNullOrEmpty(const System::String\&) method


Verifica se la stringa è nulla o vuota.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) da verificare. |

### Valore di ritorno

True se la stringa è nulla o ha lunghezza zero, false altrimenti.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Struttura [TestTools](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)