---
title: IsTest()
second_title: Aspose.Slides for C++ API Reference
description: Checks if test method exists.
type: docs
weight: 1
url: /system/testtoolsext/istest/
---
## TestToolsExt::IsTest(const char *, const char *, const char *) method


Checks if test method exists.

```cpp
static bool System::TestToolsExt::IsTest(const char *name_space, const char *class_name, const char *method_name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name_space | const char * | Namespace to look for. |
| class_name | const char * | Class to look for. |
| method_name | const char * | Method to look for. |

### Return Value

True if test method is registered, false otherwise.

## TestToolsExt::IsTest(const char *, const char *) method


Checks if test method exists.

```cpp
static bool System::TestToolsExt::IsTest(const char *class_name, const char *method_name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| class_name | const char * | Class to look for. |
| method_name | const char * | Method to look for. |

### Return Value

True if test method is registered, false otherwise.

## See Also

* Struct [TestToolsExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)