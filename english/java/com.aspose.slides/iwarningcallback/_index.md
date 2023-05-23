---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface for classes which receive warning
type: docs
weight: 1108
url: /java/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interface for classes which receive warning
## Methods

| Method | Description |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Callback method which receives warning and decides whether operation should be aborted. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Callback method which receives warning and decides whether operation should be aborted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Warning to process. |

**Returns:**
int - Abortion decision [ReturnAction](../../com.aspose.slides/returnaction).
