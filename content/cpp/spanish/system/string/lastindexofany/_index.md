---
title: LastIndexOfAny()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca cualquiera de los caracteres pasados a lo largo de toda la cadena de forma inversa. Compara el último carácter de la cadena con todos los caracteres de anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada.
type: docs
weight: 664
url: /es/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const método

Busca cualquiera de los caracteres pasados a lo largo de toda la cadena de forma inversa. Compara el último carácter de la cadena con todos los caracteres de anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |

### Valor devuelto

[Index](../../index/) del último carácter coincidente o -1 si no se encuentra.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const método

Busca cualquiera de los caracteres pasados a través de una subcadena de forma inversa. Compara el último carácter de la cadena con todos los caracteres de anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |
| startindex | **int32_t** | [Index](../../index/) para iniciar la búsqueda desde. |

### Valor devuelto

[Index](../../index/) del último carácter coincidente o -1 si no se encuentra.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const método

Busca cualquiera de los caracteres pasados a través de una subcadena de forma inversa. Compara el último carácter de la cadena con todos los caracteres de anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |
| startindex | **int32_t** | [Index](../../index/) para iniciar la búsqueda desde. |
| count | **int32_t** | Número de caracteres a examinar. |

### Valor devuelto

[Index](../../index/) del último carácter coincidente o -1 si no se encuentra.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)