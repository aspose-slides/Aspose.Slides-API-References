---
title: ComparerAdapter
second_title: Referencia de API de Aspose.Slides para C++
description: Adaptador para usar IComparer dentro del entorno STL. Utiliza IComparer si está configurado; de lo contrario, utiliza el operador < (si está disponible) o devuelve false (si no lo está).
type: docs
weight: 638
url: /es/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

Adaptador para usar [IComparer](../icomparer/) dentro del entorno STL. Utiliza [IComparer](../icomparer/) si está configurado; de lo contrario, utiliza el operador < (si está disponible) o devuelve false (si no lo está).

```cpp
template<class T>class ComparerAdapter
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo que se compara. |

## Métodos

| Método | Descripción |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Construye el adaptador sin ningún comparador disponible. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Construye el adaptador. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) función para tipos con el operador < disponible. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) función para tipos con el operador < no disponible. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Establece el objeto comparador. |

## Ver también

* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)