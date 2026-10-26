---
title: EqualityComparerHashAdapter
second_title: Referencia de API de Aspose.Slides para C++
description: Adaptador para usar IEqualityComparer para generar hash. Utiliza el objeto comparador, si está configurado; de lo contrario, utiliza el método de hash disponible seleccionado mediante la estructura DictionaryHashSelector.
type: docs
weight: 677
url: /es/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

Adaptador para usar [IEqualityComparer](../iequalitycomparer/) para generar hash. Utiliza el objeto comparador, si está configurado; de lo contrario, utiliza el método de hash disponible seleccionado mediante la estructura [DictionaryHashSelector](../dictionaryhashselector/).

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Hashed | tipo. |

## Métodos

| Método | Descripción |
| --- | --- |
| [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Crea un adaptador sin comparador para usar. |
| [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Crea un adaptador con el comparador dado para usar. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Calcula el valor hash. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Establece el comparador para usar. |

## Ver también

* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)