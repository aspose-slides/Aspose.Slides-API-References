---
title: IterateOver()
second_title: Referência da API Aspose.Slides para C++
description: "Esta propriedade de função encapsula um objeto enumerable (ou iterável) para que possa ser usado com loop baseado em intervalo. Esta sobrecarga para Enumerable sem métodos begin(), end() utiliza um argumento de tipo de destino para (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /pt/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) função


Esta propriedade de função encapsula um objeto enumerable (ou iterável) para que possa ser usado com loop baseado em intervalo. Esta sobrecarga para Enumerable sem métodos begin(), end() utiliza um argumento de tipo de destino para (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de destino, que deve ser retornado pelo iterador |
| Enumerable | O tipo do objeto encapsulado |

## System::IterateOver(System::SmartPtr\<Enumerable\>) função


Esta propriedade de função encapsula um objeto enumerable (ou iterável) para que possa ser usado com loop baseado em intervalo. Esta sobrecarga para Enumerable sem métodos begin(), end() utiliza um argumento de tipo de destino padrão para (auto& value : IterateOver(enumerable)), análoga ao seguinte código C#: foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Enumerable | O tipo do objeto encapsulado |

## System::IterateOver(System::SmartPtr\<Enumerable\>) função


Esta propriedade de função encapsula um objeto enumerable (ou iterável) para que possa ser usado com loop baseado em intervalo. Esta sobrecarga para Enumerable com métodos begin(), end() utiliza um argumento de tipo de destino padrão para (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Enumerable | O tipo do objeto encapsulado |

## System::IterateOver(System::SmartPtr\<Enumerable\>) função


Esta propriedade de função encapsula um objeto enumerable (ou iterável) para que possa ser usado com loop baseado em intervalo. Esta sobrecarga para Enumerable com métodos begin(), end() utiliza um tipo de destino igual ao value_type original do iterador.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Enumerable | O tipo do objeto encapsulado |
| T | O tipo de destino que deve ser retornado pelo iterador |

## System::IterateOver(System::SmartPtr\<Enumerable\>) função


Esta propriedade de função encapsula um objeto enumerable (ou iterável) para que possa ser usado com loop baseado em intervalo. Esta sobrecarga para Enumerable com métodos begin(), end() utiliza um tipo de destino diferente do value_type original do iterador.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Enumerable | O tipo do objeto encapsulado |
| T | O tipo de destino que deve ser retornado pelo iterador |

## System::IterateOver(const Enumerable *) função


Esta propriedade de função encapsula um objeto enumerable (ou iterável) para que possa ser usado com loop baseado em intervalo. Esta sobrecarga para Enumerable com tipo de destino padrão.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Enumerable | O tipo do objeto encapsulado |

## System::IterateOver(const Enumerable *) função


Esta propriedade de função encapsula um objeto enumerable (ou iterável) para que possa ser usado com loop baseado em intervalo. Esta sobrecarga para Enumerable sem métodos begin(), end() utiliza um argumento de tipo de destino para (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de destino, que deve ser retornado pelo iterador |
| Enumerable | O tipo do objeto encapsulado |

## Ver também

* Classe [SmartPtr](../smartptr/)
* Struct [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)