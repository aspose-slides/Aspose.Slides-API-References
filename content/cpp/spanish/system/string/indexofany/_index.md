---
title: IndexOfAny()
second_title: Referencia de la API de Aspose.Slides para C++
description: Búsqueda de caracteres hacia adelante.
type: docs
weight: 638
url: /es/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method

Búsqueda de caracteres hacia adelante.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Carácter a buscar. |
| startIndex | int | [Index](../../index/) para iniciar la búsqueda en. |

### Return Value

[Index](../../index/) de la primera posición de carácter desde startIndex o -1 si no se encuentra.

## String::IndexOfAny(const String\&, int) const method

Por lo tanto, busca todos los caracteres de str en este. Si se encuentra el primer carácter, se devuelve su posición; de lo contrario, se busca el segundo y así sucesivamente.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) de caracteres a buscar. El orden de los caracteres importa. |
| startIndex | int | Posición desde la cual iniciar la búsqueda. |

### Return Value

[Index](../../index/) del primer carácter encontrado o -1 si no se encuentra ninguno.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method

Busca cualquiera de los caracteres pasados en toda la cadena. Compara el primer carácter de la cadena con todos los caracteres de anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primer carácter que coincide con alguno de los caracteres objetivo.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |

### Return Value

[Index](../../index/) del primer carácter coincidente o -1 si no se encuentra.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method

Busca cualquiera de los caracteres pasados en la subcadena. Compara el primer carácter de la cadena con todos los caracteres de anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primer carácter que coincide con alguno de los caracteres objetivo.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |
| startindex | **int32_t** | [Index](../../index/) para iniciar la búsqueda desde. |

### Return Value

[Index](../../index/) del primer carácter coincidente o -1 si no se encuentra.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method

Busca cualquiera de los caracteres pasados en la subcadena. Compara el primer carácter de la cadena con todos los caracteres de anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primer carácter que coincide con alguno de los caracteres objetivo.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres a buscar. El orden no importa. |
| startindex | **int32_t** | [Index](../../index/) para iniciar la búsqueda desde. |
| count | **int32_t** | Número de caracteres a examinar. |

### Return Value

[Index](../../index/) del primer carácter coincidente o -1 si no se encuentra.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)