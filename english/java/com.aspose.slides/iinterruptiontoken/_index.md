---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
weight: 842
url: /java/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

This class represents the token to use for signaling long running tasks whether the interruption was requested.
## Methods

| Method | Description |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returns true if interruption was requested. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Throws an if interruption was requested. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Returns true if interruption was requested.

**Returns:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Throws an if interruption was requested.

