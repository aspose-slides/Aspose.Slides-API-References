---
title: Join()
second_title: Referencia de API de Aspose.Slides para C++
description: Concatena la matriz usando una cadena como separador.
type: docs
weight: 846
url: /es/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) method

Concatena la matriz usando una cadena como separador.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) para colocar entre los elementos de la matriz al unirlos. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) de partes para unir. |
| startIndex | int | Primer índice en la matriz desde el que comenzar a unir. |
| count | int | Número de elementos de la matriz a unir. -1 significa 'hasta que la matriz termine'. |

### Valor de retorno

[String](../) que representa los elementos de la matriz unidos.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) method

Concatena la matriz usando una cadena como separador.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) para colocar entre los elementos de la matriz al unirlos. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView de partes a unir. |
| startIndex | int | Primer índice en la matriz desde el que comenzar a unir. |
| count | int | Número de elementos de la matriz a unir. -1 significa 'hasta que la matriz termine'. |

### Valor de retorno

[String](../) que representa los elementos de la matriz unidos.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) method

Concatena la matriz usando una cadena como separador.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) para colocar entre los elementos de la matriz al unirlos. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - objeto enumerable de partes |

### Valor de retorno

[String](../) que representa los elementos unidos.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) method

Concatena la matriz usando una cadena como separador.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) para colocar entre los elementos de la matriz al unirlos. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) de partes para unir. |

### Valor de retorno

[String](../) que representa los elementos unidos.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)