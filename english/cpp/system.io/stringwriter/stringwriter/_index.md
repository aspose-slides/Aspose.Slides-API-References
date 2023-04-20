---
title: StringWriter()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of StringWriter using the specified StringBuilder and IFormatProvider.
type: docs
weight: 1
url: /cpp/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) constructor


Constructs a new instance of [StringWriter](../) using the specified StringBuilder and [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | The StringBuilder object to be used by the [StringWriter](../) being constructed |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | An [IFormatProvider](../../../system/iformatprovider/) object to be used by the object being constructed |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) constructor


Constructs a new instance of [StringWriter](../) using the specified StringBuilder and [IFormatProvider](../../../system/iformatprovider/) from the current culture.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | The StringBuilder object to be used by the [StringWriter](../) being constructed |

## StringWriter::StringWriter(const IFormatProviderPtr\&) constructor


Constructs a new instance of [StringWriter](../) using the specified [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | An [IFormatProvider](../../../system/iformatprovider/) object to be used by the object being constructed |

## StringWriter::StringWriter() constructor


Constructs a new instance of [StringWriter](../) using [IFormatProvider](../../../system/iformatprovider/) from the current culture.

```cpp
System::IO::StringWriter::StringWriter()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)