---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho trình quản lý giữ hành vi của tất cả các placeholder chân trang, ngày-giờ và số trang của bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/ipresentationheaderfootermanager/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Đại diện cho trình quản lý giữ hành vi của tất cả các placeholder chân trang, ngày-giờ và số trang của bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Thay đổi khả năng hiển thị của tất cả các placeholder tiêu đề, bao gồm notes master, notes slides và handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Thay đổi khả năng hiển thị của tất cả các placeholder chân trang, bao gồm master slides, layout slides và slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Thay đổi khả năng hiển thị của tất cả các placeholder số trang, bao gồm master slides, layout slides và slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Thay đổi khả năng hiển thị của tất cả các placeholder ngày-giờ, bao gồm master slides, layout slides và slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Đặt văn bản cho tất cả các placeholder tiêu đề, bao gồm notes master, notes slides và handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Đặt văn bản cho tất cả các placeholder chân trang, bao gồm master slides, layout slides và slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Đặt văn bản cho tất cả các placeholder ngày-giờ, bao gồm master slides, layout slides và slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Thay đổi khả năng hiển thị của các placeholder chân trang, ngày-giờ và số trang cho tất cả các slide tiêu đề và slide bố cục đầu tiên. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của tất cả các placeholder tiêu đề, bao gồm notes master, notes slides và handout master.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder tiêu đề hiển thị, nếu không - ẩn chúng. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của tất cả các placeholder chân trang, bao gồm master slides, layout slides và slides.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder chân trang hiển thị, nếu không - ẩn chúng. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của tất cả các placeholder số trang, bao gồm master slides, layout slides và slides.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder số trang hiển thị, nếu không - ẩn chúng. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của tất cả các placeholder ngày-giờ, bao gồm master slides, layout slides và slides.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder ngày-giờ hiển thị, nếu không - ẩn chúng. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Đặt văn bản cho tất cả các placeholder tiêu đề, bao gồm notes master, notes slides và handout master.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Đặt văn bản cho tất cả các placeholder chân trang, bao gồm master slides, layout slides và slides.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Đặt văn bản cho tất cả các placeholder ngày-giờ, bao gồm master slides, layout slides và slides.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Thay đổi khả năng hiển thị của các placeholder chân trang, ngày-giờ và số trang cho tất cả các slide tiêu đề và slide bố cục đầu tiên. Title slides – slides based on first layout slide (regardless of type of this first layout).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder hiển thị, nếu không - ẩn chúng. |