---
title: GetEnvironmentVariable()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de waarde van de opgegeven omgevingsvariabele die aan het huidige proces is gekoppeld.
type: docs
weight: 287
url: /nl/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) methode

Retourneert de waarde van de opgegeven omgevingsvariabele die aan het huidige proces is gekoppeld.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| variable | const [String](../../string/)\& | De string die de naam van de variabele bevat die opgehaald moet worden |

### Retourwaarde

De waarde van de opgegeven variabele

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) methode

Retourneert de waarde van de opgegeven omgevingsvariabele van de opgegeven locatie.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| variable | const [String](../../string/)\& | De string die de naam van de variabele bevat die opgehaald moet worden |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | De locatie van de variabele |

### Retourwaarde

De waarde van de opgegeven variabele

## Zie ook

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Class [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)