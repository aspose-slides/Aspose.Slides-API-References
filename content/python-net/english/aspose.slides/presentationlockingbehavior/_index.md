---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentationlockingbehavior/
---


## PresentationLockingBehavior enumeration

Represents the behavior regarding treating the [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) source (file or 
**io.RawIOBase**) while loading and working with an instance of [`IPresentation`](/slides/python-net/aspose.slides/ipresentation).

The PresentationLockingBehavior type exposes the following members:

## Fields

| Field | Description |
| :- | :- |
| LOAD_AND_RELEASE | The source will be locked only for a time of [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) constructor execution.<br/>If [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) is set to false, all BLOBs <br/>            will be loaded into memory. Otherwise, other means such a temporary files might be used.This behavior is slower than [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), and if it is possible to pass the <br/>            ownership of the source to [`IPresentation`](/slides/python-net/aspose.slides/ipresentation), it is recommended to use [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | The source will be locked for a whole lifetime of [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) instance, until it will <br/>            be disposed.<br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) is must be set to true for using <br/>            this behavior, otherwise exception will be thrown.This behavior is recommended, it is faster and consumes less memory than [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### Remarks

The source is the parameter passed to the [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) constructor. In the 
            example below, the source is the "pres.pptx" file:

            For this example, the source ("pres.pptx" file) will be locked for a [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) 
            instance lifetime, i.e. can't be changed or deleted by the other process.


### See Also
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

