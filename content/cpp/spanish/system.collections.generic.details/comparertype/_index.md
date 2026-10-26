---
title: ComparerType
second_title: Referencia de API de Aspose.Slides para C++
description: Compara elementos usando la semántica 'less'.
type: docs
weight: 144
url: /es/system.collections.generic.details/comparertype/
---
## ComparerType estructura

Compara elementos usando la semántica 'less'.

```cpp
template<typename T>class ComparerType
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de los elementos comparados. |
## Métodos

| Método | Descripción |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compara tipos de valor que implementan la interfaz [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compara tipos de valor primitivos y objetos que no implementan la interfaz [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compara tipos de punto flotante. |

## Ver también

* Espacio de nombres [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)