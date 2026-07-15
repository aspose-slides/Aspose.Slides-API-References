---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Giao diện cho các đối số tải tài nguyên bên ngoài.
type: docs
url: /vi/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Giao diện cho các đối số tải tài nguyên bên ngoài.
## Phương thức

| Method | Description |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | URI gốc của tài nguyên như được chỉ định trong bản trình chiếu đã nhập. |
| [getUri()](#getUri--) | URI của tài nguyên được sử dụng để tải xuống nếu [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) trả về [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI của tài nguyên được sử dụng để tải xuống nếu [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) trả về [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Đặt dữ liệu người dùng cung cấp của tài nguyên được sử dụng nếu [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) trả về [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


URI gốc của tài nguyên như được chỉ định trong bản trình chiếu đã nhập.

**Trả về:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI của tài nguyên được sử dụng để tải xuống nếu [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) trả về [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Ban đầu nó được đặt thành URI gốc của tài nguyên, nhưng có thể được định nghĩa lại thành bất kỳ giá trị nào.

**Trả về:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI của tài nguyên được sử dụng để tải xuống nếu [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) trả về [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Ban đầu nó được đặt thành URI gốc của tài nguyên, nhưng có thể được định nghĩa lại thành bất kỳ giá trị nào.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Đặt dữ liệu người dùng cung cấp của tài nguyên được sử dụng nếu [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) trả về [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] | Dữ liệu được cung cấp của tài nguyên byte[] |