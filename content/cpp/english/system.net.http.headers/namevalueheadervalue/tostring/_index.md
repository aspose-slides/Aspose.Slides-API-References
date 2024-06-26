---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: Analog of C# Object.ToString() method. Enables converting custom objects to string.
type: docs
weight: 79
url: /system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const method


Analog of C# [Object.ToString()](../../../system/object/tostring/) method. Enables converting custom objects to string.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### Return Value

[String](../../../system/string/) representation as provided by final class.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) method


Returns a string representation of the collection of the NameValueHeaderValue-class instances.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | The collection of the NameValueHeaderValue-class instances. |
| separator | char16_t | A string separator. |
| leadingSeparator | **bool** | The value that indicates if the string separator must be added before the first collection item. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | An instance where a string representation will be assigned. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) method


Returns a string representation of the collection of the NameValueHeaderValue-class instances.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | The collection of the NameValueHeaderValue-class instances. |
| separator | char16_t | A string separator. |
| leadingSeparator | **bool** | The value that indicates if the string separator must be added before the first collection item. |

### Return Value

A string representation of the collection of the NameValueHeaderValue-class instances.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Class [ObjectCollection](../../objectcollection/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)