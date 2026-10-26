---
title: TemplateContext
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một giao diện đối tượng mô hình cho công cụ mẫu.
type: docs
url: /vi/com.aspose.slides/templatecontext/
---
**Kế thừa:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Đại diện cho một giao diện đối tượng mô hình cho công cụ mẫu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Tạo một ngữ cảnh mẫu con. |
| [getObject()](#getObject--) | Trả về đối tượng mô hình. |
| [getOutput()](#getOutput--) | Trả về tập hợp các phần tử đầu ra của tài liệu chủ. |
| [getLocal()](#getLocal--) | Trả về bộ nhớ lưu trữ cục bộ của ngữ cảnh mẫu hiện tại. |
| [getGlobal()](#getGlobal--) | Trả về bộ nhớ lưu trữ toàn cục của tài liệu chủ. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

Tạo một ngữ cảnh mẫu con.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| subModel | TSubModel | Đối tượng mô hình con. |

**Giá trị trả về:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Ngữ cảnh mẫu mới với mô hình đã cho và tập hợp đầu ra của cha và bộ nhớ lưu trữ toàn cục.
### getObject() {#getObject--}
```
public final TObject getObject()
```

Trả về đối tượng mô hình. Đối tượng chỉ đọc.

**Giá trị trả về:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Trả về tập hợp các phần tử đầu ra của tài liệu chủ. Chỉ đọc [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Giá trị trả về:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

Trả về bộ nhớ lưu trữ cục bộ của ngữ cảnh mẫu hiện tại. Chỉ đọc [Storage](../../com.aspose.slides/storage).

**Giá trị trả về:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Trả về bộ nhớ lưu trữ toàn cục của tài liệu chủ. Chỉ đọc [Storage](../../com.aspose.slides/storage).

**Giá trị trả về:**
[Storage](../../com.aspose.slides/storage)