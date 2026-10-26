---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho bộ quản lý giữ hành vi của các trình giữ chỗ, bao gồm trình giữ chỗ tiêu đề cho mọi loại slide bản phát hành và ghi chú.
type: docs
url: /vi/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Quản lý đại diện cho hành vi của các trình giữ chỗ, bao gồm trình giữ chỗ tiêu đề cho mọi loại slide bản phát hành và ghi chú.

--------------------

Tên giao diện gốc "IBaseHandoutNotesSlideHeaderFooterManager" được rút ngắn thành "IBaseHandoutNotesSlideHeaderFooterManag" để tương thích với COM (độ dài tên kiểu không được vượt quá 39).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Lấy giá trị cho biết rằng có trình giữ chỗ tiêu đề. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Thay đổi tính hiển thị của trình giữ chỗ tiêu đề slide. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ tiêu đề slide. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Lấy giá trị cho biết rằng có trình giữ chỗ tiêu đề. Đọc kiểu boolean.

**Trả về:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Thay đổi tính hiển thị của trình giữ chỗ tiêu đề slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho trình giữ chỗ tiêu đề hiển thị, ngược lại - ẩn nó. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Đặt văn bản cho trình giữ chỗ tiêu đề slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |