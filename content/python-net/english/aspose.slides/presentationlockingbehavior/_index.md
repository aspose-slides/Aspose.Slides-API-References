---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## PresentationLockingBehavior enumeration

Represents the behavior regarding treating the :py:class:`aspose.slides.IPresentation` source (file or 
            :py:class:`System.IO.Stream`) while loading and working with an instance of :py:class:`aspose.slides.IPresentation`.

The PresentationLockingBehavior type exposes the following members:

## Fields

| Field | Description |
| :- | :- |
| LOAD_AND_RELEASE | The source will be locked only for a time of :py:class:`aspose.slides.IPresentation` constructor execution. |
| KEEP_LOCKED | The source will be locked for a whole lifetime of :py:class:`aspose.slides.IPresentation` instance, until it will <br/>            be disposed. |


### Remarks

The source is the parameter passed to the 
 constructor. In the 
            example below, the source is the "pres.pptx" file:
            

            For this example, the source ("pres.pptx" file) will be locked for a 
 
            instance lifetime, i.e. can't be changed or deleted by the other process.
            


