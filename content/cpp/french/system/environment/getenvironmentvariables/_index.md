---
title: GetEnvironmentVariables()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un dictionnaire contenant tous les noms des variables d'environnement et leurs valeurs associées au processus en cours.
type: docs
weight: 326
url: /fr/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() méthode

Retourne un dictionnaire contenant tous les noms des variables d'environnement et leurs valeurs associées au processus en cours.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) méthode

Retourne un dictionnaire contenant tous les noms des variables d'environnement et leurs valeurs provenant de l'emplacement spécifié.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | L'emplacement des variables |

### Valeur de retour

Un dictionnaire contenant tous les noms des variables d'environnement et leurs valeurs provenant de l'emplacement spécifié

## Voir aussi

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Classe [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Classe [String](../../string/)
* Struct [Environment](../)
* Espace de noms [System](../../)
* Library [Aspose.Slides](../../../)