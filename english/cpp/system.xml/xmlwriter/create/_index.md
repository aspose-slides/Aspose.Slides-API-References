---
title: Create()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new XmlWriter instance using the specified filename.
type: docs
weight: 469
url: /cpp/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const [String](../../../system/string/)\&) method


Creates a new [XmlWriter](../) instance using the specified filename.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | The file to which you want to write. The [XmlWriter](../) creates a file at the specified path and writes to it in XML 1.0 text syntax. The **outputFileName** must be a file system path. |

### Return Value

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::Create(const [String](../../../system/string/)\&, [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\>) method


Creates a new [XmlWriter](../) instance using the filename and [XmlWriterSettings](../../xmlwritersettings/) object.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | The file to which you want to write. The [XmlWriter](../) creates a file at the specified path and writes to it in XML 1.0 text syntax. The **outputFileName** must be a file system path. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### Return Value

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::Create(const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\&) method


Creates a new [XmlWriter](../) instance using the specified stream.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to write. The [XmlWriter](../) writes XML 1.0 text syntax and appends it to the specified stream. |

### Return Value

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::Create(const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\&, [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\>) method


Creates a new [XmlWriter](../) instance using the stream and [XmlWriterSettings](../../xmlwritersettings/) object.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to write. The [XmlWriter](../) writes XML 1.0 text syntax and appends it to the specified stream. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### Return Value

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::Create(const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\&) method


Creates a new [XmlWriter](../) instance using the specified TextWriter.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to which you want to write. The [XmlWriter](../) writes XML 1.0 text syntax and appends it to the specified TextWriter. |

### Return Value

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::Create(const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\&, [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\>) method


Creates a new [XmlWriter](../) instance using the TextWriter and [XmlWriterSettings](../../xmlwritersettings/) objects.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to which you want to write. The [XmlWriter](../) writes XML 1.0 text syntax and appends it to the specified TextWriter. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### Return Value

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::Create(const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\&) method


Creates a new [XmlWriter](../) instance using the specified [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | The [Text::StringBuilder](../../../system.text/stringbuilder/) to which to write to. Content written by the [XmlWriter](../) is appended to the [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Return Value

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::Create(const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\&, [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\>) method


Creates a new [XmlWriter](../) instance using the [Text::StringBuilder](../../../system.text/stringbuilder/) and [XmlWriterSettings](../../xmlwritersettings/) objects.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | The [Text::StringBuilder](../../../system.text/stringbuilder/) to which to write to. Content written by the [XmlWriter](../) is appended to the [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### Return Value

An [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::Create(const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\&) method


Creates a new [XmlWriter](../) instance using the specified [XmlWriter](../) object.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | The [XmlWriter](../) object that you want to use as the underlying writer. |

### Return Value

An [XmlWriter](../) object that is wrapped around the specified [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::Create(const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\&, [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\>) method


Creates a new [XmlWriter](../) instance using the specified [XmlWriter](../) and [XmlWriterSettings](../../xmlwritersettings/) objects.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | The [XmlWriter](../) object that you want to use as the underlying writer. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | The [XmlWriterSettings](../../xmlwritersettings/) object used to configure the new [XmlWriter](../) instance. If this is **nullptr**, a [XmlWriterSettings](../../xmlwritersettings/) with default settings is used. If the [XmlWriter](../) is being used with the XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) method, you should use the XslCompiledTransform::get_OutputSettings value to obtain an [XmlWriterSettings](../../xmlwritersettings/) object with the correct settings. This ensures that the created [XmlWriter](../) object has the correct output settings. |

### Return Value

An [XmlWriter](../) object that is wrapped around the specified [XmlWriter](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
