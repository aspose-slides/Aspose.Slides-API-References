---
title: InterruptionToken
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/interruptiontoken/
---

## InterruptionToken class

 This class represents the token to use for signaling long running tasks whether the interruption was requested.
 

## Methods

| Name | Description |
| --- | --- |
| [getNone](getnone)() | Represents an empty interruption token. Long-running operations will never be interrupted via InterruptionTokenSource#interrupt when using this token. |
| [isInterruptionRequested](isinterruptionrequested)() | Returns true if interruption was requested. |
| [throwIfInterruptionRequested](throwifinterruptionrequested)() | Throws an if interruption was requested. |
