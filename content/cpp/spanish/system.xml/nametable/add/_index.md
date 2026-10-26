---
title: Add()
second_title: Referencia de la API de Aspose.Slides para C++
description: Atomiza la cadena especificada y la agrega a NameTable.
type: docs
weight: 14
url: /es/system.xml/nametable/add/
---
## NameTable::Add(const String\&) método

Atomiza la cadena especificada y la agrega a [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | La cadena a agregar. |

### Valor de retorno

La cadena atomizada o la cadena existente si ya existe en [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) método

Atomiza la cadena especificada y la agrega a [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | La matriz de caracteres que contiene la cadena a agregar. |
| start | **int32_t** | El índice base cero en la matriz que especifica el primer carácter de la cadena. |
| len | **int32_t** | El número de caracteres en la cadena. |

### Valor de retorno

La cadena atomizada o la cadena existente si ya existe en [NameTable](../). Si **len** es cero, se devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [NameTable](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)