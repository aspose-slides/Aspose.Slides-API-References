---
title: AppendFormat()
second_title: Aspose.Slides for C++ API Reference
description: Appends formated string to builder.
type: docs
weight: 131
url: /cpp/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const [String](../../../system/string/)\&, const TArgs\&...) method


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

## See Also

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::AppendFormat(const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\&, const [String](../../../system/string/)\&, const TArgs\&...) method


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

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFormatProvider](../../../system/iformatprovider/)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
