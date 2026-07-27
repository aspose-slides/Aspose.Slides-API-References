---
title: GetEnvironmentVariables()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un diccionario que contiene todos los nombres de variables de entorno y sus valores asociados al proceso actual.
type: docs
weight: 326
url: /es/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() método

Devuelve un diccionario que contiene todos los nombres de variables de entorno y sus valores asociados al proceso actual.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) método

Devuelve un diccionario que contiene todos los nombres de variables de entorno y sus valores de la ubicación especificada.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | La ubicación de las variables |

### Valor devuelto

Un diccionario que contiene todos los nombres de variables de entorno y sus valores de la ubicación especificada

## Ver también

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Class [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Class [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)