﻿---
title: InterruptionToken class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/interruptiontoken/
---


## InterruptionToken class

This class represents the token to use for signaling long running tasks whether the interruption was requested.

The InterruptionToken type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`none`](/slides/python-net/aspose.slides/interruptiontoken/none/) | Represents an empty interruption token.<br/>Long-running operations will never be interrupted via [`InterruptionTokenSource.interrupt`](/slides/python-net/aspose.slides/interruptiontokensource/interrupt)<br/>            when using this token. |
| [`is_interruption_requested`](/slides/python-net/aspose.slides/interruptiontoken/is_interruption_requested/) | Returns **bool**.true if interruption was requested. |

## Methods

| Method | Description |
| :- | :- |
| [`throw_if_interruption_requested`](/slides/python-net/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Throws an OperationCanceledException if<br/>            interruption was requested. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

