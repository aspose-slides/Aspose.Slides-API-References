---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/loadingstreambehavior/
---
## Výčet LoadingStreamBehavior

The **io.RawIOBase** passed to a method is considered as a Binary Large Object (BLOB) (see [`IBlobManagementOptions`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions) description). Values of this enumeration identify how the **io.RawIOBase** should be treated when it passed to the method. Depending on the requirements, different decisions could be made to provide the most efficient behavior.

The LoadingStreamBehavior type exposes the following members:

## Pole

| Field | Description |
| :- | :- |
| READ_STREAM_AND_RELEASE | Stream bude čten až do konce a poté uvolněn – i.e. it will be guaranteed that this stream <br/> will not be used by [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation) instance in the future. It can be closed by the client <br/> code or used in any other way. |
| KEEP_LOCKED | Stream will be locked inside the [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation) object, i.e. the ownership of <br/> the stream will be transferred. The [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation) object will be responsible to <br/> correctly dispose the stream when this object will be disposed itself. <br/> This behavior is extremely useful when you need to serialize a large BLOB file (such as a large <br/> video or audio -see [`IBlobManagementOptions`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions) description) and want to prevent loading <br/> this file into memory or other performance issues. You may just open the **System.IO.FileStream** <br/> for this file and pass to a method, choosing [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/cs/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |


### Viz také
* třída [`IBlobManagementOptions`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions)
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)