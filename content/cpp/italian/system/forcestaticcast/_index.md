---
title: ForceStaticCast()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue un cast statico reale sugli oggetti SmartPtr.
type: docs
weight: 2588
url: /it/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) funzione

Esegue un cast statico reale su oggetti [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo puntato di destinazione. |
| TFrom | Tipo puntato di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntatore di origine. |

### Valore di ritorno

Risultato del cast se il cast è consentito, altrimenti il comportamento è indefinito.

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Struttura [CastResult](../castresult/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)