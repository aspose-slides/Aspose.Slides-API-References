---
title: GetEnvironmentVariable()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la valeur de la variable d'environnement spécifiée associée au processus actuel.
type: docs
weight: 287
url: /fr/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) method

Renvoie la valeur de la variable d'environnement spécifiée associée au processus actuel.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| variable | const [String](../../string/)\& | La chaîne contenant le nom de la variable à récupérer |

### Return Value

La valeur de la variable spécifiée

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) method

Renvoie la valeur de la variable d'environnement spécifiée depuis l'emplacement indiqué.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| variable | const [String](../../string/)\& | La chaîne contenant le nom de la variable à récupérer |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | L'emplacement de la variable |

### Return Value

La valeur de la variable spécifiée

## See Also

* Énumération [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Classe [String](../../string/)
* Structure [Environment](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)