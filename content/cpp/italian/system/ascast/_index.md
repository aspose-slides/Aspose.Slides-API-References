---
title: AsCast()
second_title: Riferimento API Aspose.Slides per C++
description: Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore 'as'. Utilizzato quando è necessario un cast semplice simile a un costruttore.
type: docs
weight: 2640
url: /it/system/ascast/
---
## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato quando è necessario un cast semplice simile a un costruttore.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato quando il tipo di origine e quello di risultato sono gli stessi.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato per wrapper di eccezioni.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast. Restituisce nullptr se non è disponibile alcuna conversione.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato per castare un oggetto a eccezione.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast. Restituisce nullptr se non è disponibile alcuna conversione.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato quando sia l'origine sia il risultato sono smart pointer.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast. Restituisce nullptr se non è disponibile alcuna conversione.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato quando sia l'origine sia il risultato sono smart pointer (con SmartPtr<...> esplicito nel tipo di risultato).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast. Restituisce nullptr se non è disponibile alcuna conversione.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato per l'unboxing di un oggetto verso nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast. Restituisce nullable vuoto se non è disponibile alcuna conversione.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Unboxing non valido verso un tipo non oggetto.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Restituisce sempre null.

## System::AsCast(const Source\&) funzione

Unboxing non valido verso un tipo non oggetto.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Restituisce sempre null.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato per il boxing di un oggetto nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato per il boxing di un oggetto comune.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato per il boxing di un oggetto comune.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato per l'unboxing di stringa.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato per il casting di nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::AsCast(const Source\&) funzione

Converte il tipo di origine nel tipo di risultato utilizzando il cast con l'operatore **as**. Utilizzato per il casting tra array.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo di origine. |
| Result | Il tipo di risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast. Restituisce nullptr se non è disponibile alcuna conversione per alcun membro dell'array.

## See Also

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)