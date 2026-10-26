---
title: StaticCast_noexcept()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue il cast statico sugli oggetti SmartPtr.
type: docs
weight: 2549
url: /it/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) funzione


Esegue il cast statico sugli oggetti [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
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

Risultato del cast se il cast è consentito o nullptr altrimenti.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa AsCast invece.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) funzione


Esegue il cast statico sugli oggetti [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo puntato di destinazione. |
| TFrom | Tipo puntato di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Puntatore di origine. |

### Valore di ritorno

Risultato del cast se il cast è consentito o nullptr altrimenti.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa AsCast invece.

## System::StaticCast_noexcept(const TFrom\&) funzione


Esegue il cast statico sugli oggetti Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo Exception di destinazione. |
| TFrom | Tipo Exception di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const TFrom\& | Puntatore di origine. |

### Valore di ritorno

Risultato del cast se il cast è consentito o nullptr altrimenti.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa AsCast invece.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) funzione


Esegue il cast statico su oggetti Objects a oggetti Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo Exception di destinazione. |
| TFrom | [Object](../object/) type. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Puntatore di origine. |

### Valore di ritorno

Risultato del cast se il cast è consentito o nullptr altrimenti.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa AsCast invece.

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Classe [WeakPtr](../weakptr/)
* Classe [Object](../object/)
* Struttura [IsExceptionWrapper](../isexceptionwrapper/)
* Struttura [CastResult](../castresult/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)