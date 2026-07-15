---
title: ExternalResourceResolver
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Lớp callback được sử dụng để giải quyết các tài nguyên bên ngoài trong quá trình nhập tài liệu Html và Svg.
type: docs
url: /vi/com.aspose.slides/externalresourceresolver/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Lớp callback được sử dụng để giải quyết các tài nguyên bên ngoài trong quá trình nhập tài liệu Html, Svg.

--------------------

Việc sử dụng resolver này có thể tạo ra lỗ hổng khi tệp HTML hoặc SVG do khách hàng cung cấp sẽ khiến phần mềm máy chủ truy cập tệp cục bộ hoặc tệp mạng. Hãy sử dụng cẩn thận. Đề nghị không chỉ định ExternalResourceResolver (chỉ các đối tượng nhúng sẽ được đọc) hoặc tạo một lớp con kiểm tra xem uri được chỉ định có hợp lệ hay không.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Giải quyết URI tuyệt đối từ URI cơ sở và URI tương đối. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Ánh xạ một URI tới một đối tượng chứa tài nguyên thực tế. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Giải quyết URI tuyệt đối từ URI cơ sở và URI tương đối.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| baseUri | java.lang.String | URI cơ sở của các đối tượng liên kết |
| relativeUri | java.lang.String | URI tương đối tới đối tượng được liên kết. |

**Giá trị trả về:**
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

**Giá trị trả về:**
java.io.InputStream - Một đối tượng InputStream hoặc null nếu không thể truyền tài nguyên.