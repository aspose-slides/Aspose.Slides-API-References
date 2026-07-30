---
title: StaticCast()
second_title: Riferimento API Aspose.Slides per C++
description: Esegue un cast statico su oggetti SmartPtr.
type: docs
weight: 2562
url: /it/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) function


Esegue un cast statico su [SmartPtr](../smartptr/) oggetti.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Valore di ritorno

Cast result if cast is allowed.

Obsoleto
:   Mantenuto per compatibilità retroattiva. Utilizzare ExplicitCast al suo posto.

## System::StaticCast(WeakPtr\<TFrom\> const\&) function


Esegue un cast statico su [WeakPtr](../weakptr/) oggetti.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Source pointer. |

### Valore di ritorno

Cast result if cast is allowed.

Obsoleto
:   Mantenuto per compatibilità retroattiva. Utilizzare ExplicitCast al suo posto.

## System::StaticCast(std::nullptr_t) function


Esegue un cast statico di oggetti null.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Target pointee type. |

### Valore di ritorno

nullptr.

Obsoleto
:   Mantenuto per compatibilità retroattiva. Utilizzare ExplicitCast al suo posto.

## System::StaticCast(TFrom) function


Specializzazione per tipi aritmetici.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) function


Esegue il cast da [String](../string/) a [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) function


Specializzazione per tipi aritmetici.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) function


Esegue un cast statico su oggetti non puntatore.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const TFrom\& | Source object. |

### Valore di ritorno

Cast result if cast is allowed.

Obsoleto
:   Mantenuto per compatibilità retroattiva. Utilizzare ExplicitCast al suo posto.

## System::StaticCast(const TFrom\&) function


Esegue un cast statico su oggetti Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Valore di ritorno

Cast result if cast is allowed.

Obsoleto
:   Mantenuto per compatibilità retroattiva. Utilizzare ExplicitCast al suo posto.

## System::StaticCast(SmartPtr\<TFrom\>) function


Esegue un cast statico su Objects a oggetti Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### Valore di ritorno

Cast result if cast is allowed.

Obsoleto
:   Mantenuto per compatibilità retroattiva. Utilizzare ExplicitCast al suo posto.

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Classe [WeakPtr](../weakptr/)
* Classe [String](../string/)
* Classe [Object](../object/)
* Struttura [IsExceptionWrapper](../isexceptionwrapper/)
* Struttura [CastResult](../castresult/)
* Struttura [IsSmartPtr](../issmartptr/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)