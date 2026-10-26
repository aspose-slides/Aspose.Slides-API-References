---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
url: /vi/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Giao diện callback dùng để quản lý việc tải tài nguyên bên ngoài.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Phương thức callback điều chỉnh việc tải tài nguyên bên ngoài. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Phương thức callback điều chỉnh việc tải tài nguyên bên ngoài.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Dữ liệu tài nguyên đang tải [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Giá trị trả về:** 
int - Quyết định tải tài nguyên [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).