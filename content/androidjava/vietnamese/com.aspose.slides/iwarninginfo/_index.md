---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho một giao diện cơ sở cho tất cả cảnh báo.
type: docs
url: /vi/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Đại diện cho một giao diện cơ sở cho tất cả cảnh báo.
## Methods

| Method | Description |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Nếu receiver không null, kết thúc cảnh báo đến receiver đã chỉ định và ném AbortRequestedException nếu receiver quyết định hủy một thao tác. |
| [getWarningType()](#getWarningType--) | Trả về loại cảnh báo. |
| [getDescription()](#getDescription--) | Trả về mô tả có thể đọc được cho người dùng của cảnh báo này. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Nếu receiver không null, kết thúc cảnh báo đến receiver đã chỉ định và ném AbortRequestedException nếu receiver quyết định hủy một thao tác.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Đối tượng receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Trả về loại cảnh báo. Chỉ đọc [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Returns:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Trả về mô tả có thể đọc được cho người dùng của cảnh báo này. Chỉ đọc String.

**Returns:**
java.lang.String