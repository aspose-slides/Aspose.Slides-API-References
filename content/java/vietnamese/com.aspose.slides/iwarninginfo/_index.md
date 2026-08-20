---
title: IWarningInfo
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một giao diện cơ bản cho tất cả các cảnh báo.
type: docs
url: /vi/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Đại diện cho một giao diện cơ bản cho tất cả các cảnh báo.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Nếu receiver không null, kết thúc cảnh báo tới một receiver được chỉ định và ném AbortRequestedException nếu receiver quyết định hủy một thao tác. |
| [getWarningType()](#getWarningType--) | Trả về một kiểu cảnh báo. |
| [getDescription()](#getDescription--) | Trả về một mô tả có thể đọc được cho con người của cảnh báo này. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Nếu receiver không null, kết thúc cảnh báo tới một receiver được chỉ định và ném AbortRequestedException nếu receiver quyết định hủy một thao tác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Đối tượng Receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Trả về một kiểu cảnh báo. Chỉ đọc [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Trả về:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Trả về một mô tả có thể đọc được cho con người của cảnh báo này. Chỉ đọc String.

**Trả về:**
java.lang.String