---
title: Cast()
second_title: Aspose.Slides per C++ Riferimento API
description: Esegue il cast su oggetti SmartPtr.
type: docs
weight: 2510
url: /it/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) function

Esegue il cast su oggetti [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo di puntatore di destinazione. |
| TFrom | Tipo di puntatore di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntatore sorgente. |

### Valore di ritorno

Risultato del cast se il cast è consentito.

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Struttura [IsExceptionWrapper](../isexceptionwrapper/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)