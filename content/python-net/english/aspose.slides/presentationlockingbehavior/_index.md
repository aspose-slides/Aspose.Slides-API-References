---
title: PresentationLockingBehavior
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentationlockingbehavior/
---


PresentationLockingBehavior enumeration

Represents the behavior regarding treating the 
[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
 source (file or 
            
.NET type System.IO.Stream
) while loading and working with an instance of 
[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
.

The PresentationLockingBehavior type exposes the following members:

## Fields

| Field | Description |
| :- | :- |
| LOAD_AND_RELEASE | The source will be locked only for a time of <br/>[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)<br/> constructor execution.<br/>            <br/>If <br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/aspose.slides/iblobmanagementoptions#is_temporary_files_allowed)<br/> is set to false, all BLOBs <br/>            will be loaded into memory. Otherwise, other means such a temporary files might be used.<br/>This behavior is slower than <br/>[`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/aspose.slides/presentationlockingbehavior#KEEP_LOCKED)<br/>, and if it is possible to pass the <br/>            ownership of the source to <br/>[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)<br/>, it is recommended to use <br/>[`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/aspose.slides/presentationlockingbehavior#KEEP_LOCKED)<br/>. |
| KEEP_LOCKED | The source will be locked for a whole lifetime of <br/>[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)<br/> instance, until it will <br/>            be disposed.<br/>            <br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/aspose.slides/iblobmanagementoptions#is_temporary_files_allowed)<br/> is must be set to true for using <br/>            this behavior, otherwise exception will be thrown.<br/>This behavior is recommended, it is faster and consumes less memory than <br/>[`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/aspose.slides/presentationlockingbehavior#LOAD_AND_RELEASE)<br/>. |


### Remarks

The source is the parameter passed to the 
[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
 constructor. In the 
            example below, the source is the "pres.pptx" file:
            

            For this example, the source ("pres.pptx" file) will be locked for a 
[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
 
            instance lifetime, i.e. can't be changed or deleted by the other process.

