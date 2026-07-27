---
title: TestTools
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona un conjunto de métodos útiles que verifican algunas propiedades básicas de diferentes tipos y funciones.
type: docs
weight: 1925
url: /es/system/testtools/
---
## TestTools struct

Proporciona un conjunto de métodos útiles que verifican algunas propiedades básicas de diferentes tipos y funciones.

```cpp
class TestTools
```

## Methods

| Método | Descripción |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Comprueba si la función lanza una excepción de cualquier tipo. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Comprueba si la cadena está vacía. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Comprueba si la colección está vacía. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Comprueba si el valor específico es nulo. [Version](../version/) para tipos aritméticos y enumeraciones. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Comprueba si el valor específico es nulo. [Version](../version/) para tipos de valor no aritméticos y no enumerados. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Comprueba si el valor específico es nulo. [Version](../version/) para tipos de valor no aritméticos. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Comprueba si el valor específico es nulo. [Version](../version/) para pares clave-valor. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Comprueba si la cadena es nula. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Comprueba si la colección es nula o está vacía. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Comprueba si la cadena es nula o está vacía. |
## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)