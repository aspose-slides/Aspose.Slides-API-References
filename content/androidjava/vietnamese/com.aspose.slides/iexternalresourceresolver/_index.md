---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to resolve external resources during Html Svg documents import.
type: docs
url: /vi/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Giao diện callback được sử dụng để giải quyết các tài nguyên bên ngoài trong quá trình nhập tài liệu Html, Svg.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Giải quyết URI tuyệt đối từ URI cơ sở và URI tương đối. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Ánh xạ một URI tới một đối tượng chứa tài nguyên thực tế. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
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
public abstract InputStream getEntity(String absoluteUri)
```

Ánh xạ một URI tới một đối tượng chứa tài nguyên thực tế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI tuyệt đối tới đối tượng. |

**Giá trị trả về:**
java.io.InputStream - Đối tượng InputStream hoặc null nếu tài nguyên không thể được truyền.