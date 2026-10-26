---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho trình quản lý chịu trách nhiệm hành vi của các placeholder, bao gồm placeholder tiêu đề cho mọi loại slide bản phát hành và ghi chú.
type: docs
url: /vi/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

Đại diện cho trình quản lý chứa hành vi của các placeholder, bao gồm placeholder tiêu đề cho mọi loại slide bản phát hành và ghi chú.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Lấy giá trị cho biết một placeholder tiêu đề có tồn tại. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Thay đổi tính hiển thị của placeholder tiêu đề slide. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Đặt văn bản cho placeholder tiêu đề slide. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

Lấy giá trị cho biết một placeholder tiêu đề có tồn tại. Đọc boolean.

**Trả về:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

Thay đổi tính hiển thị của placeholder tiêu đề slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder tiêu đề hiển thị, ngược lại - Ẩn nó. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

Đặt văn bản cho placeholder tiêu đề slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |