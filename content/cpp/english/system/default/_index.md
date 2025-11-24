---
title: Default()
second_title: Aspose.Slides for C++ API Reference
description: Returns the reference to the single default-constructed instance of the exception type.
type: docs
weight: 2159
url: /system/default/
---
## System::Default() function


Returns the reference to the single default-constructed instance of the exception type.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type whose instance is returned |

## System::Default() function


Returns the reference to the single default-constructed instance of the non-exception type.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type whose instance is returned |

## See Also

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)