---
title: IPresentationHeaderFooterManager
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho trình quản lý chứa hành vi của tất cả các placeholder chân trang, ngày-giờ và số trang của bản trình chiếu.
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
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Thay đổi khả năng hiển thị của tất cả các placeholder tiêu đề, bao gồm master ghi chú, các slide ghi chú và master tài liệu. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Thay đổi khả năng hiển thị của tất cả các placeholder chân trang, bao gồm các slide master, các slide bố cục và các slide. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Thay đổi khả năng hiển thị của tất cả các placeholder số trang, bao gồm các slide master, các slide bố cục và các slide. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Thay đổi khả năng hiển thị của tất cả các placeholder ngày-giờ, bao gồm các slide master, các slide bố cục và các slide. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Đặt văn bản cho tất cả các placeholder tiêu đề, bao gồm master ghi chú, các slide ghi chú và master tài liệu. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Đặt văn bản cho tất cả các placeholder chân trang, bao gồm các slide master, các slide bố cục và các slide. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Đặt văn bản cho tất cả các placeholder ngày-giờ, bao gồm các slide master, các slide bố cục và các slide. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Thay đổi khả năng hiển thị của các placeholder chân trang, ngày-giờ và số trang cho tất cả các slide tiêu đề và cho slide bố cục đầu tiên. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của tất cả các placeholder tiêu đề, bao gồm master ghi chú, các slide ghi chú và master tài liệu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder tiêu đề hiển thị, ngược lại - ẩn chúng. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của tất cả các placeholder chân trang, bao gồm các slide master, các slide bố cục và các slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder chân trang hiển thị, ngược lại - ẩn chúng. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của tất cả các placeholder số trang, bao gồm các slide master, các slide bố cục và các slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder số trang hiển thị, ngược lại - ẩn chúng. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của tất cả các placeholder ngày-giờ, bao gồm các slide master, các slide bố cục và các slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder ngày-giờ hiển thị, ngược lại - ẩn chúng. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Đặt văn bản cho tất cả các placeholder tiêu đề, bao gồm master ghi chú, các slide ghi chú và master tài liệu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Đặt văn bản cho tất cả các placeholder chân trang, bao gồm các slide master, các slide bố cục và các slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Đặt văn bản cho tất cả các placeholder ngày-giờ, bao gồm các slide master, các slide bố cục và các slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Thay đổi khả năng hiển thị của các placeholder chân trang, ngày-giờ và số trang cho tất cả các slide tiêu đề và cho slide bố cục đầu tiên. Slide tiêu đề – các slide dựa trên slide bố cục đầu tiên (bất kể loại của bố cục đầu tiên này).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder hiển thị, ngược lại - ẩn chúng. |