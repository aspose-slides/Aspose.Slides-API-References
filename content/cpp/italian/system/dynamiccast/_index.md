---
title: DynamicCast()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue un cast dinamico su oggetti Exception.
type: docs
weight: 2536
url: /it/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) funzione

Esegue un cast dinamico su oggetti Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
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

Risultato del cast se il cast è consentito.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa ExplicitCast invece.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) funzione

Esegue un cast dinamico su oggetti [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
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

Risultato del cast se il cast è consentito.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa ExplicitCast invece.

## System::DynamicCast(SmartPtr\<TFrom\>) funzione

Estrae il valore dell'enum incapsulato mediante cast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo enum di destinazione. |
| TFrom | Tipo puntato di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Puntatore all'oggetto da cui estrarre i dati. |

### Valore di ritorno

Valore enum estratto.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa ExplicitCast invece.

## System::DynamicCast(std::nullptr_t) funzione

Esegue un cast dinamico di oggetti null.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo puntato di destinazione. |

### Valore di ritorno

nullptr.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa ExplicitCast invece.

## System::DynamicCast(TFrom\&) funzione

Esegue un cast dinamico su oggetti non puntatore.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo di destinazione. |
| TFrom | Tipo di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | TFrom\& | Oggetto di origine. |

### Valore di ritorno

Risultato del cast.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa ExplicitCast invece.

## System::DynamicCast(SmartPtr\<TFrom\>) funzione

Esegue un cast dinamico su oggetti Objects a oggetti Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo Exception di destinazione. |
| TFrom | Tipo [Object](../object/) di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Puntatore di origine. |

### Valore di ritorno

Risultato del cast se il cast è consentito.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa ExplicitCast invece.

## System::DynamicCast(TFrom) funzione

Esegue un cast dinamico da IntPtr a puntatore.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Tipo di destinazione. |
| TFrom | Tipo di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | TFrom | Valore IntPtr di origine. |

### Valore di ritorno

Risultato del cast.

Deprecata
:   Mantenuta per compatibilità retroattiva. Usa ExplicitCast invece.

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Classe [Object](../object/)
* Struttura [IsExceptionWrapper](../isexceptionwrapper/)
* Struttura [CastResult](../castresult/)
* Struttura [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)