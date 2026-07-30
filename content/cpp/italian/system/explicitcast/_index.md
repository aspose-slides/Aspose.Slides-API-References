---
title: ExplicitCast()
second_title: Aspose.Slides per C++ Riferimento API
description: Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato quando i tipi sorgente e risultato sono gli stessi.
type: docs
weight: 2627
url: /it/system/explicitcast/
---
## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato quando i tipi sorgente e risultato sono gli stessi.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato quando è necessario un cast semplice simile a un costruttore.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per wrapper di eccezioni.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per convertire un oggetto in un’eccezione.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato quando sorgente e risultato sono entrambi smart pointer (senza SmartPtr<...> esplicito nel tipo risultato).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(Source) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato quando si converte un puntatore grezzo in uno smart pointer.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | Source | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato quando sorgente e risultato sono entrambi smart pointer (con SmartPtr<...> esplicito nel tipo risultato).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per unboxing di oggetti in nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per boxare un nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per unboxing di oggetti nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per il boxing di enum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per copiare tipi valore sul heap quando il tipo valore deve essere referenziato come smart pointer (in generici vincolati a un’interfaccia ma specializzati con una struttura che implementa tale interfaccia).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per ottenere interfacce da tipi valore.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per boxing comune.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per il boxing di [System::String](../string/).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per unboxing di interfacce.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per unboxing comune.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per cast a nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## System::ExplicitCast(const Source\&) funzione

Converte il tipo sorgente nel tipo risultato usando un cast esplicito. Utilizzato per il cast tra array.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Source | Il tipo sorgente. |
| Result | Il tipo risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) da convertire. |

### Valore di ritorno

Il risultato del cast.

## Vedi anche

* Typedef [Exception](../exception/)
* Classe [SmartPtr](../smartptr/)
* Classe [BoxedValueBase](../boxedvaluebase/)
* Struttura [CastResult](../castresult/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)