---
title: BaseDictionary()
second_title: Aspose.Slides for C++ API Reference
description: Creates empty data structure.
type: docs
weight: 14
url: /cpp/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() constructor


Creates empty data structure.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) constructor


Forwarding constructor to push arguments into underlying map constructor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Args | Types of arguments to forward to map. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | int | Arguments to forward to underlying map. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) constructor


Copying constructor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Args | Types of map constructor arguments. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) to copy data from. |
| args | const Args\&... | Arguments to forward to underlying map constructor. |

## BaseDictionary::BaseDictionary(BaseType *) constructor


Copying constructor.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) to copy data from. |

## See Also

* Typedef [BaseType](../basetype/)
* Class [BaseDictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)