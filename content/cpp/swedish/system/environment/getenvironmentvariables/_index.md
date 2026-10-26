---
title: GetEnvironmentVariables()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en ordbok som innehåller alla miljövariablers namn och deras värden som är associerade med den aktuella processen.
type: docs
weight: 326
url: /sv/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() metod

Returnerar en dictionary som innehåller alla miljövariablers namn och deras värden som är associerade med den aktuella processen.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) metod

Returnerar en dictionary som innehåller alla miljövariablers namn och deras värden från den angivna platsen.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Platsen för variablerna |

### Returvärde

En dictionary som innehåller alla miljövariablers namn och deras värden från den angivna platsen

## Se även

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Class [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Class [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)