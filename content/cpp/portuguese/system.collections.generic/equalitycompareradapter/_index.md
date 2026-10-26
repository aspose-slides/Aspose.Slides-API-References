---
title: EqualityComparerAdapter
second_title: Referência da API Aspose.Slides para C++
description: "Adaptador que possibilita o uso de IEqualityComparer com coleções e algoritmos no estilo STL. Usa IEqualityComparer, se definido. Caso não esteja definido, usa o operador ==, Object::Equals ou T::Equals, o que estiver disponível."
type: docs
weight: 664
url: /pt/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adaptador que possibilita o uso de [IEqualityComparer](../iequalitycomparer/) com coleções e algoritmos no estilo STL. Usa [IEqualityComparer](../iequalitycomparer/), se definido. Caso não esteja definido, usa o operador ==, [Object::Equals](../../system/object/equals/) ou T::Equals, o que estiver disponível.

```cpp
template<class T>class EqualityComparerAdapter
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo que está sendo comparado. |
## Métodos

| Método | Descrição |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Cria adaptador que não usa nenhum comparador. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Cria adaptador com o comparador fornecido. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Compara dois objetos. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Define o comparador. |

## Veja Também

* Namespace [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)