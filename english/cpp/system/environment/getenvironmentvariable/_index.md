---
title: GetEnvironmentVariable()
second_title: Aspose.Slides for C++ API Reference
description: Returns the value of the specified environment varibale associated with the current process.
type: docs
weight: 287
url: /cpp/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) method


Returns the value of the specified environment varibale associated with the current process.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| variable | const [String](../../string/)\& | The string containing the name of the variable to retrieve |

### Return Value

The value of the specified variable

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) method


Returns the value of the specified environment varibale from the specified location.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| variable | const [String](../../string/)\& | The string containing the name of the variable to retrieve |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | The location of the variable |

### Return Value

The value of the specified variable

## See Also

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Class [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)