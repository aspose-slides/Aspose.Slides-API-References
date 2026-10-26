---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Biểu diễn trình quản lý giữ hành vi của các placeholder footer, ngày-giờ, số trang của slide bố cục và tất cả các placeholder con.
type: docs
url: /vi/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Biểu diễn trình quản lý giữ hành vi của placeholder footer, ngày-giờ, số trang của slide bố cục và tất cả các placeholder con. Placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Thay đổi khả năng hiển thị của placeholder footer của layout slide và tất cả các placeholder footer con. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Thay đổi khả năng hiển thị của placeholder số trang của layout slide và tất cả các placeholder số trang con. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Thay đổi khả năng hiển thị của placeholder ngày-giờ của layout slide và tất cả các placeholder ngày-giờ con. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Đặt văn bản cho placeholder footer của layout slide và tất cả các placeholder footer con. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Đặt văn bản cho placeholder ngày-giờ của layout slide và tất cả các placeholder ngày-giờ con. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của placeholder footer của layout slide và tất cả các placeholder footer con. Placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder footer hiển thị, ngược lại - ẩn chúng. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của placeholder số trang của layout slide và tất cả các placeholder số trang con. Placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào layout slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder số trang hiển thị, ngược lại - ẩn chúng. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của placeholder ngày-giờ của layout slide và tất cả các placeholder ngày-giờ con. Placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào layout slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder ngày-giờ hiển thị, ngược lại - ẩn chúng. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Đặt văn bản cho placeholder footer của layout slide và tất cả các placeholder footer con. Placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào layout slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Đặt văn bản cho placeholder ngày-giờ của layout slide và tất cả các placeholder ngày-giờ con. Placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào layout slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |