---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Giao diện cho các lớp nhận cảnh báo
type: docs
url: /vi/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Giao diện cho các lớp nhận cảnh báo
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Phương thức callback nhận cảnh báo và quyết định liệu hoạt động có nên bị hủy không. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Phương thức callback nhận cảnh báo và quyết định liệu hoạt động có nên bị hủy không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Cảnh báo để xử lý. |

**Giá trị trả về:**
int - Quyết định hủy [ReturnAction](../../com.aspose.slides/returnaction).