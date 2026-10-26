---
title: GetEnvironmentVariable()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el valor de la variable de entorno especificada asociada al proceso actual.
type: docs
weight: 287
url: /es/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) método

Devuelve el valor de la variable de entorno especificada asociada al proceso actual.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| variable | const [String](../../string/)\& | La cadena que contiene el nombre de la variable a recuperar |

### Valor devuelto

El valor de la variable especificada

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) método

Devuelve el valor de la variable de entorno especificada desde la ubicación indicada.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| variable | const [String](../../string/)\& | La cadena que contiene el nombre de la variable a recuperar |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | La ubicación de la variable |

### Valor devuelto

El valor de la variable especificada

## Ver también

* Enumeración [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Clase [String](../../string/)
* Estructura [Environment](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)