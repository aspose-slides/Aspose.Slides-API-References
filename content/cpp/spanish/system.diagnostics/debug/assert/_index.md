---
title: Assert()
second_title: Referencia de API de Aspose.Slides para C++
description: Asegure la condición y envíe información en caso de fallo.
type: docs
weight: 14
url: /es/system.diagnostics/debug/assert/
---
## Debug::Assert(bool) método


Asegura la condición y envía información en caso de fallo.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| condition | **bool** | Valor de la condición. |

## Debug::Assert(bool, const String\&) método


Asegura la condición y envía información en caso de fallo.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| condition | **bool** | Valor de la condición. |
| message | const [String](../../../system/string/)\& | Mensaje a rellenar al fallar la aserción. |

## Debug::Assert(bool, const char *) método


Asegura la condición y envía información en caso de fallo.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const char *message)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| condition | **bool** | Valor de la condición. |
| message | const char * | Mensaje a rellenar al fallar la aserción. |

## Debug::Assert(bool, const String\&, const String\&) método


Asegura la condición y envía información en caso de fallo.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message, const String &detailMessage)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| condition | **bool** | Valor de la condición. |
| message | const [String](../../../system/string/)\& | Mensaje a rellenar al fallar la aserción. |
| detailMessage | const [String](../../../system/string/)\& | Mensaje detallado a rellenar al fallar la aserción. |

## Ver también

* Clase [String](../../../system/string/)
* Estructura [Debug](../)
* Espacio de nombres [System::Diagnostics](../../)
* Biblioteca [Aspose.Slides](../../../)