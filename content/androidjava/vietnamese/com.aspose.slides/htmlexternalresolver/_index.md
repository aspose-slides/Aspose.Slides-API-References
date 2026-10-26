---
title: HtmlExternalResolver
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đối tượng callback được sử dụng bởi quy trình nhập HTML để lấy các đối tượng được tham chiếu như hình ảnh.
type: docs
url: /vi/com.aspose.slides/htmlexternalresolver/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Đối tượng callback được sử dụng bởi quy trình nhập HTML để lấy các đối tượng tham chiếu như hình ảnh.

--------------------

Việc sử dụng resolver này có thể tạo ra lỗ hổng khi tệp HTML do client cung cấp khiến phần mềm máy chủ truy cập tệp cục bộ hoặc mạng. Hãy sử dụng cẩn thận. Được đề xuất không chỉ định HtmlExternalResolver (chỉ các đối tượng được nhúng sẽ được đọc) hoặc tạo một lớp con kiểm tra xem uri được chỉ định có hợp lệ hay không.
## Các phương thức khởi tạo

| Phương thức khởi tạo | Mô tả |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Giải quyết URI tuyệt đối từ các URI cơ sở và tương đối. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Ánh xạ một URI tới một đối tượng chứa tài nguyên thực tế. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Giải quyết URI tuyệt đối từ các URI cơ sở và tương đối.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| baseUri | java.lang.String | URI cơ sở của các đối tượng liên kết |
| relativeUri | java.lang.String | URI tương đối tới đối tượng được liên kết. |

**Trả về:**
java.lang.String - URI tuyệt đối hoặc null nếu không thể giải quyết URI tương đối.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Ánh xạ một URI tới một đối tượng chứa tài nguyên thực tế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI tuyệt đối tới đối tượng. |

**Trả về:**
java.io.InputStream - Một đối tượng InputStream hoặc null nếu tài nguyên không thể được truyền phát.