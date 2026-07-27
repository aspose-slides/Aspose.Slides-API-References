---
title: Get()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve la cadena atomizada con el valor especificado.
type: docs
weight: 27
url: /es/system.xml/nametable/get/
---
## NameTable::Get(const String\&) método

Devuelve la cadena atomizada con el valor especificado.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | El nombre a buscar. |

### Valor devuelto

El objeto de cadena atomizada o **nullptr** si la cadena no se ha atomizado previamente.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) método

Devuelve la cadena atomizada que contiene los mismos caracteres que el rango especificado de caracteres en la matriz dada.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | La matriz de caracteres que contiene el nombre a buscar. |
| start | **int32_t** | El índice basado en cero en la matriz que especifica el primer carácter del nombre. |
| len | **int32_t** | El número de caracteres en el nombre. |

### Valor devuelto

La cadena atomizada o **nullptr** si la cadena no se ha atomizado previamente. Si **len** es cero, se devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [NameTable](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)