---
title: ToBase64String()
second_title: Referencia de API de Aspose.Slides para C++
description: Base-64 codifica los elementos del arreglo de bytes especificado y devuelve los datos codificados como una cadena.
type: docs
weight: 40
url: /es/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) método


Codifica en base-64 los elementos del arreglo de bytes especificado y devuelve los datos codificados como una cadena.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | El arreglo de bytes a codificar |
| insert_line_breaks | **bool** | Especifica si se deben insertar caracteres de salto de línea en la cadena de salida después de cada 76 caracteres base-64 |

### Valor devuelto

La cadena que contiene la representación codificada en base-64 del arreglo de entrada

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) método


Codifica en base-64 un rango de elementos del arreglo de bytes especificado y devuelve los datos codificados como una cadena.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | El arreglo de bytes que contiene el rango de elementos a codificar |
| offset_in | int | Un índice de un elemento en el arreglo de entrada donde comienza el rango a codificar |
| length | int | La longitud del rango de elementos a codificar |
| insert_line_breaks | **bool** | Especifica si se deben insertar caracteres de salto de línea en la cadena de salida después de cada 76 caracteres base-64 |

### Valor devuelto

La cadena que contiene la representación codificada en base-64 del rango de elementos del arreglo de entrada

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) método


Codifica en base-64 los elementos del arreglo de bytes especificado y devuelve los datos codificados como una cadena.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | El arreglo de bytes a codificar |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Especifica opciones de formato de los datos codificados en base-64 |

### Valor devuelto

La cadena que contiene la representación codificada en base-64 del arreglo de entrada

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) método


Codifica en base-64 un rango de elementos del arreglo de bytes especificado y devuelve los datos codificados como una cadena.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | El arreglo de bytes que contiene el rango de elementos a codificar |
| offset_in | int | Un índice de un elemento en el arreglo de entrada donde comienza el rango a codificar |
| length | int | La longitud del rango de elementos a codificar |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Especifica opciones de formato de los datos codificados en base-64 |

### Valor devuelto

La cadena que contiene la representación codificada en base-64 del rango de elementos del arreglo de entrada

## Ver también

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)