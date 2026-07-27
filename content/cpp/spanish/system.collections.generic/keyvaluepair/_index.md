---
title: KeyValuePair
second_title: Referencia de API de Aspose.Slides para C++
description: "Par de clave y valor. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 378
url: /es/system.collections.generic/keyvaluepair/
---
## KeyValuePair clase

Par de clave y valor. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use [System::SmartPtr](../../system/smartptr/) clase para gestionar objetos de este tipo.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Métodos

| Método | Descripción |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Obtiene la clave. |
| const TValue\& [get_Value](./get_value/)() const | Obtiene el valor. |
| int [GetHashCode](./gethashcode/)() const | Calcula el hash del par clave-valor XORando los hashes de la clave y del valor. |
| **bool** [IsNull](./isnull/)() const | Siempre devuelve false. |
| [KeyValuePair](./keyvaluepair/)() | Inicializador de par clave-valor nulo. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Constructor. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Constructor de conversión de tipo. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Parche para clases heredadas de IComparer<KeyValuePair<TKey, TValue>>, no compara nada. |
| [String](../../system/string/) [ToString](./tostring/)() const | Convierte el par clave-valor a cadena. |

## Véase también

* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)