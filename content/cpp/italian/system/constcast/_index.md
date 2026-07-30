---
title: ConstCast()
second_title: Aspose.Slides per C++ Riferimento API
description: Fine dei cast deprecati.
type: docs
weight: 2575
url: /it/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) funzione


Fine dei cast deprecati.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo di puntatore di destinazione. |
| TFrom | Tipo di puntatore di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Puntatore di origine. |

### Valore di ritorno

Risultato del cast se il cast è consentito, altrimenti nullptr.
## Osservazioni


Esegue un cast const su oggetti [SmartPtr](../smartptr/).

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Struttura [CastResult](../castresult/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)