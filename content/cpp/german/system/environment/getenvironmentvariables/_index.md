---
title: GetEnvironmentVariables()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Wörterbuch zurück, das alle Namen der Umgebungsvariablen und deren Werte enthält, die dem aktuellen Prozess zugeordnet sind.
type: docs
weight: 326
url: /de/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() Methode

Gibt ein Wörterbuch zurück, das alle Namen der Umgebungsvariablen und deren Werte enthält, die dem aktuellen Prozess zugeordnet sind.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```
## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) Methode

Gibt ein Wörterbuch zurück, das alle Namen der Umgebungsvariablen und deren Werte aus dem angegebenen Speicherort enthält.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```
### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Der Ort der Variablen |

### Rückgabewert

Ein Wörterbuch, das alle Namen der Umgebungsvariablen und deren Werte aus dem angegebenen Speicherort enthält.

## Siehe auch

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Klasse [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Klasse [String](../../string/)
* Struktur [Environment](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)