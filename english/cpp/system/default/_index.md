---
title: Default()
second_title: Aspose.Slides for C++ API Reference
description: Returns the default-constructed instance of the specified type.
type: docs
weight: 2055
url: /cpp/system/default/
---
## System::Default() function


Returns the default-constructed instance of the specified type.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type whose instance is returned |

## System::Default() function


Returns the default-constructed instance of the specified type.

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