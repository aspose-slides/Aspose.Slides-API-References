---
title: IsNullOrEmpty()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si la colección es nula o está vacía.
type: docs
weight: 27
url: /es/system/testtools/isnullorempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) method

Comprueba si la colección es nula o está vacía.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
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

True si la colección es nula o tiene un recuento de elementos cero, false en caso contrario.

## TestTools::IsNullOrEmpty(const System::String\&) method

Comprueba si la cadena es nula o está vacía.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) a comprobar. |

### Valor devuelto

True si la cadena es nula o tiene longitud cero, false en caso contrario.

## Véase también

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)