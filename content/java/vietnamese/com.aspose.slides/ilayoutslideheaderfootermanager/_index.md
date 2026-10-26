---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides cho Tham chiếu API Java
description: Đại diện cho trình quản lý nắm giữ hành vi của các placeholder chân trang, ngày-giờ, số trang của slide bố cục và tất cả các placeholder con.
type: docs
url: /vi/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Đại diện cho trình quản lý nắm giữ hành vi của các placeholder chân trang, ngày-giờ, số trang của slide bố cục và tất cả các placeholder con. Các placeholder con có nghĩa là các placeholder được chứa trên các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Thay đổi khả năng hiển thị của placeholder chân trang slide bố cục và tất cả các placeholder chân trang con. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Thay đổi khả năng hiển thị của placeholder số trang slide bố cục và tất cả các placeholder số trang con. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Thay đổi khả năng hiển thị của placeholder ngày-giờ slide bố cục và tất cả các placeholder ngày-giờ con. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Đặt văn bản cho placeholder chân trang slide bố cục và tất cả các placeholder chân trang con. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Đặt văn bản cho placeholder ngày-giờ slide bố cục và tất cả các placeholder ngày-giờ con. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của placeholder chân trang slide bố cục và tất cả các placeholder chân trang con. Các placeholder con có nghĩa là các placeholder được chứa trên các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide master.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder chân trang hiển thị, ngược lại - ẩn chúng. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của placeholder số trang slide bố cục và tất cả các placeholder số trang con. Các placeholder con có nghĩa là các placeholder được chứa trên các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder số trang hiển thị, ngược lại - ẩn chúng. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của placeholder ngày-giờ slide bố cục và tất cả các placeholder ngày-giờ con. Các placeholder con có nghĩa là các placeholder được chứa trên các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder ngày-giờ hiển thị, ngược lại - ẩn chúng. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Đặt văn bản cho placeholder chân trang slide bố cục và tất cả các placeholder chân trang con. Các placeholder con có nghĩa là các placeholder được chứa trên các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Đặt văn bản cho placeholder ngày-giờ slide bố cục và tất cả các placeholder ngày-giờ con. Các placeholder con có nghĩa là các placeholder được chứa trên các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |