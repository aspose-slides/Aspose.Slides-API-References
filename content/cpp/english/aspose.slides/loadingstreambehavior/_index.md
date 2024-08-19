---
title: LoadingStreamBehavior
second_title: Aspose.Slides for C++ API Reference
description: "The System::IO::Stream passed to a method is considered as a Binary Large Object (BLOB) (see IBlobManagementOptions description). Values of this enumeration identify how the System::IO::Stream should be treated when it passed to the method. Depending on the requirements, different decisions could be made to provide the most efficient behavior."
type: docs
weight: 6501
url: /aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum


The [System::IO::Stream](../../system.io/stream/) passed to a method is considered as a Binary Large Object (BLOB) (see [IBlobManagementOptions](../iblobmanagementoptions/) description). Values of this enumeration identify how the [System::IO::Stream](../../system.io/stream/) should be treated when it passed to the method. Depending on the requirements, different decisions could be made to provide the most efficient behavior.

```cpp
enum class LoadingStreamBehavior
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | The stream will be read to the end and then released - i.e. it will be guaranteed that this stream will not be used by [IPresentation](../ipresentation/) instance in the future. It can be closed by the client code or used in any other way. |
| KeepLocked | 1 | The stream will be locked inside the [IPresentation](../ipresentation/) object, i.e. the ownership of the stream will be transferred. The [IPresentation](../ipresentation/) object will be responsible to correctly dispose the stream when this object will be disposed itself. This behavior is extremely useful when you need to serialize a large BLOB file (such as a large video or audio -see [IBlobManagementOptions](../iblobmanagementoptions/) description) and want to prevent loading this file into memory or other performance issues. You may just open the [System::IO::FileStream](../../system.io/filestream/) for this file and pass to a method, choosing [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## See Also

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)