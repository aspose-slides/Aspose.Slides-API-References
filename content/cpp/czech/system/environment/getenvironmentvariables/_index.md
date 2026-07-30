---
title: GetEnvironmentVariables()
second_title: Aspose.Slides pro C++ referenční API
description: Vrací slovník obsahující všechna jména proměnných prostředí a jejich hodnoty spojené s aktuálním procesem.
type: docs
weight: 326
url: /cs/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() metoda

Vrací slovník obsahující všechna jména proměnných prostředí a jejich hodnoty spojené s aktuálním procesem.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) metoda

Vrací slovník obsahující názvy proměnných prostředí a jejich hodnoty ze zadaného umístění.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Umístění proměnných |

### Návratová hodnota

Slovník obsahující názvy proměnných prostředí a jejich hodnoty ze zadaného umístění

## Viz také

* Výčet [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Třída [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Třída [String](../../string/)
* Struktura [Environment](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)