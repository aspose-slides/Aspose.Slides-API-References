---
title: IterateOver()
second_title: Riferimento API Aspose.Slides per C++
description: "Questa proprietà di funzione avvolge un oggetto enumerabile (o iterabile) in modo che possa essere utilizzato con un ciclo for basato su intervallo. Questa sovraccarico per Enumerable senza metodi begin(), end() con argomento di tipo target per (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /it/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) funzione


Questa proprietà di funzione avvolge un oggetto enumerabile (o iterabile) in modo che possa essere utilizzato con un ciclo for basato su intervallo. Questa sovraccarico per Enumerable senza metodi begin(), end() con argomento di tipo target per (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo target, deve essere restituito dall'iteratore |
| Enumerable | Il tipo dell'oggetto avvolto |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funzione


Questa proprietà di funzione avvolge un oggetto enumerabile (o iterabile) in modo che possa essere utilizzato con un ciclo for basato su intervallo. Questa sovraccarico per Enumerable senza metodi begin(), end() con tipo target predefinito per (auto& value : IterateOver(enumerable)) analogo al seguente codice C# foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Enumerable | Il tipo dell'oggetto avvolto |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funzione


Questa proprietà di funzione avvolge un oggetto enumerabile (o iterabile) in modo che possa essere utilizzato con un ciclo for basato su intervallo. Questa sovraccarico per Enumerable con metodi begin(), end() con tipo target predefinito per (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Enumerable | Il tipo dell'oggetto avvolto |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funzione


Questa proprietà di funzione avvolge un oggetto enumerabile (o iterabile) in modo che possa essere utilizzato con un ciclo for basato su intervallo. Questa sovraccarico per Enumerable con metodi begin(), end() con tipo target uguale al value_type originale dell'iteratore.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Enumerable | Il tipo dell'oggetto avvolto |
| T | Il tipo target che deve essere restituito dall'iteratore |

## System::IterateOver(System::SmartPtr\<Enumerable\>) funzione


Questa proprietà di funzione avvolge un oggetto enumerabile (o iterabile) in modo che possa essere utilizzato con un ciclo for basato su intervallo. Questa sovraccarico per Enumerable con metodi begin(), end() con tipo target diverso dal value_type originale dell'iteratore.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Enumerable | Il tipo dell'oggetto avvolto |
| T | Il tipo target che deve essere restituito dall'iteratore |

## System::IterateOver(const Enumerabile *) funzione


Questa proprietà di funzione avvolge un oggetto enumerabile (o iterabile) in modo che possa essere utilizzato con un ciclo for basato su intervallo. Questa sovraccarico per Enumerabile con tipo target predefinito.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Enumerable | Il tipo dell'oggetto avvolto |

## System::IterateOver(const Enumerabile *) funzione


Questa proprietà di funzione avvolge un oggetto enumerabile (o iterabile) in modo che possa essere utilizzato con un ciclo for basato su intervallo. Questa sovraccarico per Enumerabile senza metodi begin(), end() con argomento di tipo target per (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo target, deve essere restituito dall'iteratore |
| Enumerable | Il tipo dell'oggetto avvolto |

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Struttura [IsSmartPtr](../issmartptr/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)