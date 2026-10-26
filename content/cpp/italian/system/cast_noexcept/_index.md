---
title: Cast_noexcept()
second_title: Riferimento API Aspose.Slides per C++
description: Esegue il cast sugli oggetti SmartPtr.
type: docs
weight: 2497
url: /it/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) funzione

Esegue il cast sugli oggetti [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo dell'oggetto puntato di destinazione. |
| TFrom | Tipo dell'oggetto puntato di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntatore di origine. |

### Valore restituito

Risultato del cast se il cast è consentito o nullptr altrimenti.

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Struttura [IsExceptionWrapper](../isexceptionwrapper/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)