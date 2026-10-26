---
title: ToBase64CharArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Base-64 codifica un rango de elementos en el arreglo de bytes especificado y almacena los datos codificados como un arreglo de caracteres Unicode.
type: docs
weight: 27
url: /es/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) método


Base-64 codifica un rango de elementos en el arreglo de bytes especificado y almacena los datos codificados como un arreglo de caracteres Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | El arreglo de bytes que contiene el rango de elementos a codificar |
| offset_in | int | Un índice de un elemento en el arreglo de entrada donde comienza el rango a codificar |
| length | int | La longitud del rango de elementos a codificar |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Una referencia constante al arreglo de salida donde se colocarán los datos resultantes |
| offset_out | int | Un índice en el arreglo de salida donde comenzar a colocar los datos resultantes |
| insert_line_breaks | **bool** | Especifica si los caracteres de salto de línea deben insertarse en el arreglo de salida después de cada 76 caracteres base-64 |

### Valor devuelto

El número de caracteres escritos en el arreglo de salida

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) método


Base-64 codifica un rango de elementos en el arreglo de bytes especificado y almacena los datos codificados como un arreglo de caracteres Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | El arreglo de bytes que contiene el rango de elementos a codificar |
| offset_in | int | Un índice de un elemento en el arreglo de entrada donde comienza el rango a codificar |
| length | int | La longitud del rango de elementos a codificar |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Una referencia constante al arreglo de salida donde se colocarán los datos resultantes |
| offset_out | int | Un índice en el arreglo de salida donde comenzar a colocar los datos resultantes |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Especifica las opciones de formato de los datos codificados en base-64 |

### Valor devuelto

El número de caracteres escritos en el arreglo de salida

## Ver también

* Enumeración [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Estructura [Convert](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)