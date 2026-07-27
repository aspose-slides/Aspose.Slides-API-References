---
title: BitVector32
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona un vector de bits ligero y sencillo con acceso entero o Booleano fácil a un almacenamiento de 32 bits.
type: docs
weight: 1
url: /es/system.collections.specialized/bitvector32/
---
## BitVector32 clase


Proporciona un vector de bits ligero y simple con acceso entero fácil o [Boolean](../../system/boolean/) a un almacenamiento de 32 bits.

```cpp
class BitVector32
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Inicializa una nueva instancia vacía del [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Inicializa una nueva instancia de la estructura [BitVector32](./) con los datos internos especificados. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Inicializa una nueva instancia de la estructura [BitVector32](./) con la información del valor especificado. |
| static **int32_t** [CreateMask](./createmask/)() | Crea la primera máscara de una serie. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Crea la siguiente máscara de una serie. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Crea la primera sección de una serie, con el valor máximo especificado. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Crea la siguiente sección de una serie, con el valor máximo especificado. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Determina si el objeto especificado es el mismo que el actual. |
| **int32_t** [get_Data](./get_data/)() | devuelve los datos sin procesar almacenados en este vector de bits... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Obtiene un valor que indica si todos los bits especificados están establecidos. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Obtiene el valor de la sección especificada. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Establece un valor que indica si todos los bits especificados están establecidos. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Establece el valor para la sección especificada. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Convierte el valor representado por el parámetro value a cadena. |
| [String](../../system/string/) [ToString](./tostring/)() const | Convierte el valor representado por el objeto actual a cadena. |

## Ver también

* Espacio de nombres [System::Collections::Specialized](../)
* Biblioteca [Aspose.Slides](../../)