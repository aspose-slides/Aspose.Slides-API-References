---
title: ITemplateEngine
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một công cụ mẫu chuyển đổi cặp mẫu và dữ liệu thành đầu ra kết quả thường là HTML.
type: docs
url: /vi/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Đại diện cho một công cụ mẫu chuyển đổi cặp mẫu và dữ liệu thành đầu ra kết quả (thường là HTML).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Thêm mẫu vào bộ sưu tập mẫu. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Chuyển đổi mẫu với khóa đã cho và đối tượng mô hình thành đầu ra. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Thêm mẫu vào bộ sưu tập mẫu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| key | java.lang.String | Khóa cho mẫu trong bộ sưu tập mẫu. |
| template | java.lang.String | Nội dung mẫu. |
| modelType | com.aspose.ms.System.Type | Kiểu của đối tượng mô hình cho mẫu. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Chuyển đổi mẫu với khóa đã cho và đối tượng mô hình thành đầu ra.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| key | java.lang.String | Khóa cho mẫu trong bộ sưu tập mẫu. |
| model | java.lang.Object | Đối tượng mô hình với dữ liệu để chuyển đổi. |

**Trả về:**
java.lang.String - Đầu ra kết quả dưới dạng String.