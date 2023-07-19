---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Represents the source of .
type: docs
weight: 847
url: /java/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Represents the source of [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Methods

| Method | Description |
| --- | --- |
| [getToken()](#getToken--) | Returns new token binded to this [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returns true if interruption requested, false otherwise. |
| [interrupt()](#interrupt--) | Intialize request for interruption. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Returns new token binded to this [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Returns:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Returns true if interruption requested, false otherwise.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Intialize request for interruption.

