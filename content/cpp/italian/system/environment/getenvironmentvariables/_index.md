---
title: GetEnvironmentVariables()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce un dizionario contenente tutti i nomi delle variabili d'ambiente e i loro valori associati al processo corrente.
type: docs
weight: 326
url: /it/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() metodo

Restituisce un dizionario contenente tutti i nomi delle variabili d'ambiente e i loro valori associati al processo corrente.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) metodo

Restituisce un dizionario contenente tutti i nomi delle variabili d'ambiente e i loro valori dalla posizione specificata.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | La posizione delle variabili |

### Valore restituito

Un dizionario contenente tutti i nomi delle variabili d'ambiente e i loro valori dalla posizione specificata

## Vedi anche

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Classe [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Classe [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)