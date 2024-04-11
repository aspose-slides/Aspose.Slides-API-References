---
title: InterruptionToken
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/interruptiontoken/
---


InterruptionToken class

This class represents the token to use for signaling long running tasks whether the interruption was requested.

The InterruptionToken type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [none](/slides/python-net/aspose.slides/interruptiontoken/none/) | Represents an empty interruption token.<br/>            <br/>Long-running operations will never be interrupted via <br/>[`InterruptionTokenSource.interrupt`](/slides/python-net/aspose.slides/interruptiontokensource/interrupt)<br/><br/>            when using this token. |
| [is_interruption_requested](/slides/python-net/aspose.slides/interruptiontoken/is_interruption_requested/) | Returns <br/>.NET type System.Boolean<br/>.true if interruption was requested. |

## Methods

| Method | Description |
| :- | :- |
| [throw_if_interruption_requested](/slides/python-net/aspose.slides/interruptiontoken/interruptiontoken/#/) | Throws an <br/>OperationCanceledException<br/> if<br/>            interruption was requested. |

