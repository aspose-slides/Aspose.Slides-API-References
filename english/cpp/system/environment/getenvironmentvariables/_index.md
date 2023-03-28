---
title: GetEnvironmentVariables()
second_title: Aspose.Slides for C++ API Reference
description: Returns a dictionary containing all environment variables names and their values associated with the current process.
type: docs
weight: 326
url: /cpp/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() method


Returns a dictionary containing all environment variables names and their values associated with the current process.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## See Also

* Class [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Class [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Environment::GetEnvironmentVariables([EnvironmentVariableTarget](../../environmentvariabletarget/)) method


Returns a dictionary containing all environment variables' names and their values from the specified location.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | The location of the variables |

### Return Value

A dictionary containing all environment variables' names and their values from the specified location

## See Also

* Class [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Class [String](../../string/)
* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
