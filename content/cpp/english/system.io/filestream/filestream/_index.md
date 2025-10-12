---
title: FileStream()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of FileStream class and initializes it with the specified parameters.
type: docs
weight: 1
url: /system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) constructor


Constructs a new instance of [FileStream](../) class and initializes it with the specified parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to open. |
| mode | [FileMode](../../filemode/) | Specifies the mode in which to open the file. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor


Constructs a new instance of [FileStream](../) class and initializes it with the specified parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to open. |
| mode | [FileMode](../../filemode/) | Specifies the mode in which to open the file. |
| access | [FileAccess](../../fileaccess/) | The requested access type. |
| share | [FileShare](../../fileshare/) | The type of access that other [FileStream](../) objects have to the opened file. |
| buffer_size | **int32_t** | The number of bytes bufferred during read and write operations. |
| options | [FileOptions](../../fileoptions/) | Additional options. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor


Constructs a new instance of [FileStream](../) class and initializes it with the specified parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to open. |
| mode | [FileMode](../../filemode/) | Specifies the mode in which to open the file. |
| access | [FileAccess](../../fileaccess/) | The requested access type. |
| share | [FileShare](../../fileshare/) | The type of access that other [FileStream](../) objects have to the opened file. |
| buffer_size | **int32_t** | The number of bytes bufferred during read and write operations. |
| useAsync | **bool** | Specifies whether to use asynchronous I/O or synchronous I/O. |
## Remarks



The underlying operating system might not support asynchronous I/O. 

## FileStream::FileStream(const FileStream\&) constructor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## See Also

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [String](../../../system/string/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)