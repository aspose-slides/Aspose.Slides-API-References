---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: Reads a single character from the input stream.
type: docs
weight: 66
url: /cpp/system.io/binaryreader/read/
---
## BinaryReader::Read() method


Reads a single character from the input stream.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### Return Value

Read character encoded with UTF-16 encoding; if the read character is represented by two codepoints in UTF-16 encoding then only the high surragate is returned.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) method


Reads the specified number of bytes from the input stream and writes them to the specified byte array.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array to write the read bytes to |
| index | int | A 0-based position in **buffer** to start writing at |
| count | int | The number of bytes to read |

### Return Value

The number of bytes read

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) method


Reads the specified number of characters from the input stream, converts them to UTF-16 encoding and writes the resulting UTF-16 characters to the specified character array starting at the specified position.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | The UTF-16 character array to write the characters read from the input stream to |
| index | int | A 0-based index in **buffer** at which to start writing |
| count | int | The number of characters to read from the stream |

### Return Value

The number of characters read from the input stream

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)