---
title: CharacterRange
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un rango de posiciones de caracteres en una cadena. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 40
url: /es/system.drawing/characterrange/
---
## CharacterRange clase

Representa un rango de posiciones de caracteres en una cadena. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class CharacterRange
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Construye una nueva instancia de la clase [CharacterRange](./) que representa el rango especificado. |
|  [CharacterRange](./characterrange/)() | Construye una nueva instancia de la clase [CharacterRange](./) que representa un rango vacío. |
| **int32_t** [get_First](./get_first/)() const | Devuelve la posición del primer carácter del rango representado por el objeto actual. |
| **int32_t** [get_Length](./get_length/)() const | Devuelve el número de caracteres en el rango representado por el objeto actual. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Determina si el objeto actual y el especificado representan rangos distintos. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Determina si el objeto actual y el especificado representan el mismo rango. |
| void [set_First](./set_first/)(**int32_t**) | Establece la posición del primer carácter del rango representado por el objeto actual. |
| void [set_Length](./set_length/)(**int32_t**) | Devuelve el número de caracteres en el rango representado por el objeto actual. |
## Ver también

* Espacio de nombres [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)