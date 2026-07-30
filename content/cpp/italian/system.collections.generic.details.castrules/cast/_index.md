---
title: Cast()
second_title: Riferimento API Aspose.Slides per C++
description: Esegue il cast del tipo di origine al tipo di risultato. Utilizzato quando i tipi di origine e risultato sono gli stessi.
type: docs
weight: 14
url: /it/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) funzione

Esegue il cast del tipo di origine al tipo di risultato. Utilizzato quando i tipi di origine e di risultato sono gli stessi.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Valore di ritorno

Il risultato del cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) funzione

Esegue il cast del tipo di origine al tipo di risultato. Utilizzato quando il tipo di origine può essere convertito staticamente al tipo di risultato.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Valore di ritorno

Il risultato del cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) funzione

Esegue il cast del tipo di origine al tipo di risultato. Utilizzato quando i tipi non sono gli stessi e il tipo di origine non può essere convertito staticamente al tipo di risultato.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Valore di ritorno

Il risultato del cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) funzione

Esegue il cast del tipo di origine al tipo di risultato. Utilizzato quando il tipo di origine viene incapsulato nella classe [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Valore di ritorno

Il risultato del cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) funzione

Esegue il cast del tipo di origine al tipo di risultato. Utilizzato quando il tipo di origine viene estratto dall'istanza della classe [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Valore di ritorno

Il risultato del cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) funzione

Esegue il cast del tipo di origine al tipo di risultato. Utilizzato quando il tipo di origine viene incapsulato nella classe [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Valore di ritorno

Il risultato del cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) funzione

Esegue il cast del tipo di origine al tipo di risultato. Utilizzato quando il tipo di origine viene estratto dall'istanza della classe [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Valore di ritorno

Il risultato del cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) funzione

Esegue il cast del tipo di origine al tipo di risultato. Utilizzato quando il cast è non valido o la conversione è esplicita.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Valore di ritorno

Il risultato del cast.

## Vedi anche

* Struttura [CastType](../casttype/)
* Spazio dei nomi [System::Collections::Generic::Details::CastRules](../)
* Libreria [Aspose.Slides](../../)