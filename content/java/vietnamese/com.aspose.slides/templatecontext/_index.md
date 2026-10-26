---
title: TemplateContext
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một giao diện đối tượng mô hình cho một công cụ mẫu.
type: docs
url: /vi/com.aspose.slides/templatecontext/
---
**Kế thừa:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Biểu diễn một giao diện đối tượng mô hình cho một công cụ mẫu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Tạo một ngữ cảnh mẫu con. |
| [getObject()](#getObject--) | Trả về đối tượng mô hình. |
| [getOutput()](#getOutput--) | Trả về tập hợp các phần tử đầu ra của tài liệu chủ. |
| [getLocal()](#getLocal--) | Trả về bộ nhớ cục bộ của ngữ cảnh mẫu hiện tại. |
| [getGlobal()](#getGlobal--) | Trả về bộ nhớ toàn cục của tài liệu chủ. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Tạo một ngữ cảnh mẫu con.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | |
| subModel | TSubModel | Đối tượng mô hình con. |

**Trả về:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Ngữ cảnh mẫu mới với mô hình đã cho và tập hợp đầu ra của cha và bộ nhớ toàn cục.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Trả về đối tượng mô hình. Chỉ đọc Object.

**Trả về:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Trả về tập hợp các phần tử đầu ra của tài liệu chủ. Chỉ đọc [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Trả về:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Trả về bộ nhớ cục bộ của ngữ cảnh mẫu hiện tại. Chỉ đọc [Storage](../../com.aspose.slides/storage).

**Trả về:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Trả về bộ nhớ toàn cục của tài liệu chủ. Chỉ đọc [Storage](../../com.aspose.slides/storage).

**Trả về:**
[Storage](../../com.aspose.slides/storage)