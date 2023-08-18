---
title: InterruptionToken
second_title: Aspose.Slides for Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
weight: 258
url: /com.aspose.slides/interruptiontoken/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

This class represents the token to use for signaling long running tasks whether the interruption was requested.
## Methods

| Method | Description |
| --- | --- |
| [getNone()](#getNone--) | Represents an empty interruption token. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returns true if interruption was requested. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Throws an if interruption was requested. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Represents an empty interruption token.

--------------------

Long-running operations will never be interrupted via [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) when using this token.

**Returns:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Returns true if interruption was requested.

**Returns:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Throws an if interruption was requested.

