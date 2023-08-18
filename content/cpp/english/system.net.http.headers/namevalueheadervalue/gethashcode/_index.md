---
title: GetHashCode()
second_title: Aspose.Slides for C++ API Reference
description: Analog of C# Object.GetHashCode() method. Enables hashing of custom objects.
type: docs
weight: 53
url: /system.net.http.headers/namevalueheadervalue/gethashcode/
---
## NameValueHeaderValue::GetHashCode() const method


Analog of C# [Object.GetHashCode()](../../../system/object/gethashcode/) method. Enables hashing of custom objects.

```cpp
int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode() const override
```


### Return Value

Hash code value as calculated by corresponding class.

## NameValueHeaderValue::GetHashCode(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) method


Returns a hash code of all the collection items.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | The collection of the NameValueHeaderValue-class instances. |

### Return Value

A hash code of all the collection items.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [ObjectCollection](../../objectcollection/)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)