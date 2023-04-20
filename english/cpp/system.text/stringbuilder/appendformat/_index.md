---
title: AppendFormat()
second_title: Aspose.Slides for C++ API Reference
description: Appends formated string to builder.
type: docs
weight: 131
url: /cpp/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) method


Appends formated string to builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TArgs | Arguments type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Format string. |
| args | const TArgs\&... | Arguments to insert into format string positions. |

### Return Value

This pointer.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) method


Appends formated string to builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TArgs | Arguments type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Format provider; ignored. |
| format | const [String](../../../system/string/)\& | Format string. |
| args | const TArgs\&... | Arguments to insert into format string positions. |

### Return Value

This pointer.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [IFormatProvider](../../../system/iformatprovider/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)