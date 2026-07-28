---
title: GetEnvironmentVariables()
second_title: Aspose.Slides dla C++ – Odniesienie API
description: Zwraca słownik zawierający wszystkie nazwy zmiennych środowiskowych oraz ich wartości powiązane z bieżącym procesem.
type: docs
weight: 326
url: /pl/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() metoda


Zwraca słownik zawierający wszystkie nazwy zmiennych środowiskowych i ich wartości powiązane z bieżącym procesem.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) metoda


Zwraca słownik zawierający wszystkie nazwy zmiennych środowiskowych i ich wartości z określonej lokalizacji.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```


### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Lokalizacja zmiennych |

### Return Value

Słownik zawierający wszystkie nazwy zmiennych środowiskowych oraz ich wartości z określonej lokalizacji

## See Also

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Class [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Class [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)