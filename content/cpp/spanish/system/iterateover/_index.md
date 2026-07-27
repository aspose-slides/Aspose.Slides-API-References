---
title: IterateOver()
second_title: Referencia de API de Aspose.Slides para C++
description: "Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle basado en rango. Esta sobrecarga para Enumerable sin métodos begin(), end() con argumento de tipo objetivo para (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /es/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) función


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle basado en rango. Esta sobrecarga para Enumerable sin métodos begin(), end() con argumento de tipo objetivo para (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo objetivo, debe ser devuelto por el iterador |
| Enumerable | El tipo del objeto envuelto |

## System::IterateOver(System::SmartPtr\<Enumerable\>) función


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle basado en rango. Esta sobrecarga para Enumerable sin métodos begin(), end() con argumento de tipo objetivo por defecto para (auto& value : IterateOver(enumerable)) análoga al siguiente código C# `foreach (var value in enumerable)`

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo del objeto envuelto |

## System::IterateOver(System::SmartPtr\<Enumerable\>) función


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle basado en rango. Esta sobrecarga para Enumerable con métodos begin(), end() con argumento de tipo objetivo por defecto para (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo del objeto envuelto |

## System::IterateOver(System::SmartPtr\<Enumerable\>) función


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle basado en rango. Esta sobrecarga para Enumerable con métodos begin(), end() con el tipo objetivo igual al `value_type` original del iterador.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo del objeto envuelto |
| T | El tipo objetivo que debe ser devuelto por el iterador |

## System::IterateOver(System::SmartPtr\<Enumerable\>) función


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle basado en rango. Esta sobrecarga para Enumerable con métodos begin(), end() con tipo objetivo diferente al `value_type` original del iterador.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo del objeto envuelto |
| T | El tipo objetivo que debe ser devuelto por el iterador |

## System::IterateOver(const Enumerable *) función


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle basado en rango. Esta sobrecarga para Enumerable con tipo objetivo por defecto.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo del objeto envuelto |

## System::IterateOver(const Enumerable *) función


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle basado en rango. Esta sobrecarga para Enumerable sin métodos begin(), end() con argumento de tipo objetivo para (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo objetivo, debe ser devuelto por el iterador |
| Enumerable | El tipo del objeto envuelto |

## Ver también

* Clase [SmartPtr](../smartptr/)
* Estructura [IsSmartPtr](../issmartptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)