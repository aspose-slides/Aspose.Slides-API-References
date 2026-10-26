---
title: Nullable
second_title: Referencia de API de Aspose.Slides para C++
description: Declaración adelantada.
type: docs
weight: 1106
url: /es/system/nullable/
---
## Nullable clase

Declaración adelantada.

```cpp
template<typename T>class Nullable
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de valor subyacente que es ampliado por la clase [Nullable](./) |

## Métodos

| Método | Descripción |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Determina si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](./) especificado. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Determina si el objeto actual representa algún valor. |
| T [get_Value](./get_value/)() const | Devuelve una copia del valor representado por el objeto actual. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Devuelve el valor representado por el objeto actual o el valor especificado si el valor representado por el objeto actual es nulo. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Determina si el objeto actual representa un valor nulo. |
| [Nullable](./nullable/)() | Construye una instancia que representa un valor nulo. |
| [Nullable](./nullable/)(std::nullptr_t) | Construye una instancia que representa nulo. |
| [Nullable](./nullable/)(const T1\&) | Construye una instancia de la clase [Nullable](./) que representa el valor especificado convertido (si es necesario) al valor del tipo subyacente T. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Construye una instancia que representa un valor que es representado por el objeto [Nullable](./) especificado. El objeto nullable especificado puede representar un valor de tipo diferente al tipo subyacente de la instancia construida, en cuyo caso el valor representado se convierte a un valor de tipo T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Función auxiliar para comprobar si este y **other** no son nulos y llamar a una lambda en ese caso. Utilizada en implementaciones. |
| [operator const T &](./operator_const_t__and/)() const | Devuelve una referencia constante al valor representado por el objeto actual. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determina si el valor representado por el objeto actual no es nulo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Determina si el valor representado por el objeto actual no es igual al valor especificado. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Determina si el valor representado por el objeto actual no es igual al valor representado por el objeto [Nullable](./) especificado. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Aplica [operator&=()](./operator_and_equal/) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Devuelve una instancia construida por defecto de la clase Nullable<T>. |
| auto [operator+](./operator_plus/)(const T1\&) const | Suma valores nullable y no nullable. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Suma valores nullable. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Restablece el objeto actual para que represente un valor nulo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Aplica [operator+=()](./operator_plus_equal/) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Aplica [operator+=()](./operator_plus_equal/) al valor representado por el objeto actual usando el valor representado por el objeto [Nullable](./) especificado como argumento del lado derecho. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Resta valores nullable y valores apuntados a nulo. |
| auto [operator-](./operator_minus/)(const T1\&) const | Resta valores nullable y no nullable. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Resta valores nullable. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Devuelve una instancia de la clase [Nullable](./) que representa un valor nulo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Aplica [operator-=()](./operator_minus_equal/) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Aplica [operator-=()](./operator_minus_equal/) al valor representado por el objeto actual usando el valor representado por el objeto [Nullable](./) especificado como argumento del lado derecho. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Siempre devuelve false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Determina si el valor representado por el objeto actual es menor que el valor especificado aplicando [operator<()](./operator_less/) a estos valores. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Determina si el valor representado por el objeto actual es menor que el valor representado por el objeto [Nullable](./) especificado aplicando [operator<()](./operator_less/) a estos valores. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Siempre devuelve false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Determina si el valor representado por el objeto actual es menor o igual que el valor especificado aplicando [operator<=()](./operator_less_equal/) a estos valores. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Determina si el valor representado por el objeto actual es menor o igual que el valor representado por el objeto [Nullable](./) especificado aplicando [operator<=()](./operator_less_equal/) a estos valores. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Asigna un nulo al objeto actual. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Reemplaza el valor actualmente representado del objeto con el especificado. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Reemplaza el valor actualmente representado del objeto con el especificado. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determina si el valor representado por el objeto actual es nulo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Determina si el valor representado por el objeto actual es igual al valor especificado. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Determina si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](./) especificado. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Siempre devuelve false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Determina si el valor representado por el objeto actual es mayor que el valor especificado aplicando [operator>()](./operator_greater/) a estos valores. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Determina si el valor representado por el objeto actual es mayor que el valor representado por el objeto [Nullable](./) especificado aplicando [operator>()](./operator_greater/) a estos valores. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Siempre devuelve false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Determina si el valor representado por el objeto actual es mayor o igual que el valor representado por el objeto especificado aplicando [operator>=()](./operator_greater_equal/) a estos valores. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Determina si el valor representado por el objeto actual es mayor o igual que el valor representado por el objeto [Nullable](./) especificado aplicando [operator>=()](./operator_greater_equal/) a estos valores. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Aplica [operator|=()](./operator_or_equal/) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho. |
| void [reset](./reset/)() | Establece el valor actualmente representado a nulo. |
| void [set_Value](./set_value/)(const T\&) | Establece un nuevo valor al objeto nullable. |
| [String](../string/) [ToString](./tostring/)() const | Convierte el valor representado por el objeto actual a cadena. |

## Alias de tipos

| Alias | Descripción |
| --- | --- |
| [ValueType](./valuetype/) | Un alias para un tipo del valor representado por esta clase. |

## Observaciones

Representa un valor del tipo especificado que puede asignarse a nulo. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)