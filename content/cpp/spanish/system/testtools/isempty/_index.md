---
title: IsEmpty()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si la cadena está vacía.
type: docs
weight: 14
url: /es/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) método

Comprueba si la cadena está vacía.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) para comprobar si está vacía. |

### Valor devuelto

True if string is empty (null-length), false otherwise.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) método

Comprueba si la colección está vacía.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de colección. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Colección a comprobar. |

### Valor devuelto

True if collection has zero element count, false otherwise.

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Struct [TestTools](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)