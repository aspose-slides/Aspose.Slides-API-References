---
title: XmlTextWriter()
second_title: Aspose.Slides for C++ API Reference
description: Creates an instance of the XmlTextWriter class using the specified stream and encoding.
type: docs
weight: 183
url: /system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Creates an instance of the [XmlTextWriter](../) class using the specified stream and encoding.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream to which you want to write. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | The encoding to generate. If encoding is **nullptr** it writes out the stream as UTF-8 and omits the encoding attribute from the **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor


Creates an instance of the [XmlTextWriter](../) class using the specified file.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | The filename to write to. If the file exists, it truncates it and overwrites it with the new content. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | The encoding to generate. If encoding is **nullptr** it writes the file out as UTF-8 and omits the encoding attribute from the **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor


Creates an instance of the [XmlTextWriter](../) class using the specified TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | The TextWriter to write to. It is assumed that the TextWriter is already set to the correct encoding. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Class [TextWriter](../../../system.io/textwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)