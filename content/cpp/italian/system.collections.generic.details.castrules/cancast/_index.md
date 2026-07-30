---
title: CanCast()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica la possibilità di cast.
type: docs
weight: 40
url: /it/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) funzione


Verifica la possibilità di cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Valore di ritorno

True quando un valore non nullptr viene restituito dopo il cast, altrimenti false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funzione


Verifica la possibilità di cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Valore di ritorno

True quando un valore non nullptr viene restituito dopo il cast, altrimenti false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funzione


Verifica la possibilità di cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Valore di ritorno

True quando un valore non nullptr viene restituito dopo il cast, altrimenti false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funzione


Verifica la possibilità di cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Valore di ritorno

Restituisce sempre true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funzione


Verifica la possibilità di cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Valore di ritorno

True quando un valore non nullptr viene restituito dopo il cast, altrimenti false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funzione


Verifica la possibilità di cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Valore di ritorno

Restituisce sempre true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funzione


Verifica la possibilità di cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Valore di ritorno

True se l'operazione di cast è stata eseguita con successo, altrimenti false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funzione


Verifica la possibilità di cast.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Valore di ritorno

Restituisce sempre false.

## Vedi anche

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)