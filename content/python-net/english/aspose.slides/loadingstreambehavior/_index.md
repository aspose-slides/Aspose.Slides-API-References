---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/loadingstreambehavior/
---


## LoadingStreamBehavior enumeration

The **io.RawIOBase** passed to a method is considered as a Binary Large Object (BLOB) (see 
            [`IBlobManagementOptions`](/slides/python-net/aspose.slides/iblobmanagementoptions) description). Values of this enumeration identify how 
            the **io.RawIOBase** should be treated when it passed to the method. Depending on the 
            requirements, different decisions could be made to provide the most efficient behavior.

The LoadingStreamBehavior type exposes the following members:

## Fields

| Field | Description |
| :- | :- |
| READ_STREAM_AND_RELEASE | The stream will be read to the end and then released - i.e. it will be guaranteed that this stream <br/>            will not be used by [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) instance in the future. It can be closed by the client <br/>            code or used in any other way. |
| KEEP_LOCKED | The stream will be locked inside the [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) object, i.e. the ownership of <br/>            the stream will be transferred. The [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) object will be responsible to <br/>            correctly dispose the stream when this object will be disposed itself. <br/>            This behavior is extremely useful when you need to serialize a large BLOB file (such as a large <br/>            video or audio -see [`IBlobManagementOptions`](/slides/python-net/aspose.slides/iblobmanagementoptions) description) and want to prevent loading <br/>            this file into memory or other performance issues. You may just open the **System.IO.FileStream** <br/>            for this file and pass to a method, choosing [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/aspose.slides/loadingstreambehavior#KEEP_LOCKED) LoadingStreamBehavior. |

### See Also
* class [`IBlobManagementOptions`](/slides/python-net/aspose.slides/iblobmanagementoptions)
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
