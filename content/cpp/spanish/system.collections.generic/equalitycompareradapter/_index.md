---
title: EqualityComparerAdapter
second_title: Referencia de API de Aspose.Slides para C++
description: "Adaptador que permite usar IEqualityComparer con colecciones y algoritmos estilo STL. Usa IEqualityComparer, si está configurado. Si no está configurado, usa el operador ==, Object::Equals o T::Equals, lo que esté disponible."
type: docs
weight: 664
url: /es/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter estructura

Adaptador que permite usar [IEqualityComparer](../iequalitycomparer/) con colecciones y algoritmos estilo STL. Usa [IEqualityComparer](../iequalitycomparer/), si está configurado. Si no está configurado, usa el operador ==, [Object::Equals](../../system/object/equals/) o T::Equals, lo que esté disponible.

```cpp
template<class T>class EqualityComparerAdapter
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo que se compara. |

## Métodos

| Método | Descripción |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Crea un adaptador que no usa ningún comparador. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Crea un adaptador con el comparador proporcionado. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Compara dos objetos. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Establece el comparador. |

## Ver también

* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)