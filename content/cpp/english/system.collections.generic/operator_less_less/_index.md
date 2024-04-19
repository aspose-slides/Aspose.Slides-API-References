---
title: operator<<()
second_title: Aspose.Slides for C++ API Reference
description: Insert data into the stream using UTF-8 encoding.
type: docs
weight: 703
url: /system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) function


Insert data into the stream using UTF-8 encoding.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::ostream\& | Output stream to insert data to. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) to insert. |

### Return Value

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) function


Insert data into the stream.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::wostream\& | Output stream to insert data to. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) to insert. |

### Return Value

**stream**.

## See Also

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)