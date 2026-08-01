---
title: GetEnvironmentVariables()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een woordenboek met alle namen van omgevingsvariabelen en hun waarden die aan het huidige proces zijn gekoppeld.
type: docs
weight: 326
url: /nl/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() methode

Retourneert een woordenboek met alle namen van omgevingsvariabelen en hun waarden die aan het huidige proces zijn gekoppeld.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) methode

Retourneert een woordenboek met alle namen van omgevingsvariabelen en hun waarden van de opgegeven locatie.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | De locatie van de variabelen |

### Retourwaarde

Een woordenboek met alle namen van omgevingsvariabelen en hun waarden van de opgegeven locatie

## Zie ook

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Klasse [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Klasse [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)