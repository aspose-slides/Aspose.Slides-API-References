---
title: DynamicCast_noexcept()
second_title: Riferimento API Aspose.Slides per C++
description: Vecchi cast obsoleti. Verranno rimossi nelle versioni future.
type: docs
weight: 2523
url: /it/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) funzione


Vecchi cast obsoleti. Verranno rimossi nelle versioni future.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo di eccezione di destinazione. |
| TFrom | Tipo di eccezione di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const TFrom\& | Puntatore di origine. |

### Valore di ritorno

Risultato del cast se il cast è consentito o nullptr altrimenti.
## Osservazioni


Esegue il cast dinamico su oggetti Exception. Deprecato
:   Mantenuto per compatibilità retroattiva. Usare AsCast invece.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) funzione


Esegue il cast dinamico su oggetti [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo di elemento puntato di destinazione. |
| TFrom | Tipo di elemento puntato di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntatore di origine. |

### Valore di ritorno

Risultato del cast se il cast è consentito o nullptr altrimenti.

Deprecato
:   Mantenuto per compatibilità retroattiva. Usare AsCast invece.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) funzione


Esegue il cast dinamico su oggetti Objects a oggetti Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo di eccezione di destinazione. |
| TFrom | [Object](../object/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Puntatore di origine. |

### Valore di ritorno

Risultato del cast se il cast è consentito o nullptr altrimenti.

Deprecato
:   Mantenuto per compatibilità retroattiva. Usare AsCast invece.

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Classe [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)