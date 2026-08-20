---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho trình quản lý giữ hành vi của các placeholder, bao gồm placeholder tiêu đề cho tất cả các loại slide handout và notes.
type: docs
url: /vi/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Đại diện cho trình quản lý giữ hành vi của các placeholder, bao gồm placeholder tiêu đề cho tất cả các loại slide handout và notes.

--------------------

Tên giao diện gốc "IBaseHandoutNotesSlideHeaderFooterManager" đã bị cắt ngắn thành "IBaseHandoutNotesSlideHeaderFooterManag" để tương thích với COM (độ dài tên kiểu không được vượt quá 39 ký tự).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Lấy giá trị cho biết một placeholder tiêu đề có tồn tại. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Thay đổi khả năng hiển thị của placeholder tiêu đề slide. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Đặt văn bản cho placeholder tiêu đề slide. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Lấy giá trị cho biết một placeholder tiêu đề có tồn tại. Đọc boolean.

**Kết quả trả về:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Thay đổi khả năng hiển thị của placeholder tiêu đề slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder tiêu đề hiển thị, ngược lại - ẩn nó. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Đặt văn bản cho placeholder tiêu đề slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |