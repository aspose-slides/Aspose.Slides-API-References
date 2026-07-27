---
title: ToString()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte todos los valores del arreglo de bytes especificado en su representación de cadena hexadecimal. El caso de las letras a usar en la notación hexadecimal y el separador insertado entre cada par de bytes adyacentes se especifican mediante los argumentos correspondientes.
type: docs
weight: 157
url: /es/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) method

Convierte todos los valores del arreglo de bytes especificado en su representación de cadena hexadecimal. El caso de las letras a usar en la notación hexadecimal y el separador insertado entre cada par de bytes adyacentes se especifican mediante los argumentos correspondientes.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| uppercase | **bool** | Especifica el caso de las letras a usar en la representación hexadecimal resultante |
| separator | const [String](../../string/)\& | Una cadena utilizada como separador insertado entre cada par de bytes adyacentes en la cadena resultante |

### Valor devuelto

[String](../../string/) que contiene la representación hexadecimal del arreglo de bytes especificado

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) method

Convierte los valores del arreglo de bytes especificado en su representación de cadena hexadecimal comenzando en el índice especificado.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo especificado donde comenzar a convertir |

### Valor devuelto

[String](../../string/) que contiene la representación hexadecimal del rango especificado de elementos del arreglo especificado

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) method

Convierte un rango de valores del arreglo de bytes especificado en su representación de cadena hexadecimal.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contiene los bytes a convertir |
| startIndex | int | [Index](../../index/) en el arreglo especificado donde comienza el rango de los elementos del arreglo de bytes a convertir |
| length | int | La longitud del rango de los elementos del arreglo de bytes a convertir |

### Valor devuelto

[String](../../string/) que contiene la representación hexadecimal del rango especificado de elementos del arreglo especificado

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [String](../../string/)
* Clase [BitConverter](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)