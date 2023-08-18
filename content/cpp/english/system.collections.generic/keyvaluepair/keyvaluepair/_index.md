---
title: KeyValuePair()
second_title: Aspose.Slides for C++ API Reference
description: Null key-value pair initializer.
type: docs
weight: 1
url: /system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() constructor


Null key-value pair initializer.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) constructor


Constructor.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| key | const TKey\& | Key. |
| value | const TValue\& | Value. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) constructor


Type conversion constructor.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| OtherK | Other key type. |
| OtherV | Other value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | Pair value. |

## See Also

* Class [KeyValuePair](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)