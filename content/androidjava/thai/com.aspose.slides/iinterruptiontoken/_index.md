---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /th/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

This class represents the token to use for signaling long running tasks whether the interruption was requested.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | ส่งคืนค่า true หากมีการขอการขัดจังหวะ. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | ขว้างข้อยกเว้นหากมีการขอการขัดจังหวะ. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


ส่งคืนค่า true หากมีการขอการขัดจังหวะ.

**คืนค่า:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


ขว้างข้อยกเว้นหากมีการขอการขัดจังหวะ.