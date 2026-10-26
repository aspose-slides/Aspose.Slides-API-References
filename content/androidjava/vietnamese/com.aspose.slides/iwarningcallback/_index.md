---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Giao diện cho các lớp nhận cảnh báo
type: docs
url: /vi/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Giao diện cho các lớp nhận cảnh báo
## Methods

| Method | Description |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Phương thức callback nhận cảnh báo và quyết định liệu thao tác có nên bị hủy hay không. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Phương thức callback nhận cảnh báo và quyết định liệu thao tác có nên bị hủy hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Cảnh báo để xử lý. |

**Giá trị trả về:**
int - Quyết định hủy [ReturnAction](../../com.aspose.slides/returnaction).