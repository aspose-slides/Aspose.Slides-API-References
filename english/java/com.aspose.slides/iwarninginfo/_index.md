---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Represents a base interface for all warnings.
type: docs
weight: 1109
url: /java/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Represents a base interface for all warnings.
## Methods

| Method | Description |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | If receiver is not null ends warning to a specified receiver and throws the AbortRequestedException if receiver decided to abort a operation. |
| [getWarningType()](#getWarningType--) | Returns a type of warning. |
| [getDescription()](#getDescription--) | Returns a human readable description of this warning. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


If receiver is not null ends warning to a specified receiver and throws the AbortRequestedException if receiver decided to abort a operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver object [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


Returns a type of warning. Read-only [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Returns:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Returns a human readable description of this warning. Read-only String.

**Returns:**
java.lang.String
