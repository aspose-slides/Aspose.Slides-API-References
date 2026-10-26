---
title: LayoutSlideHeaderFooterManager
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho trình quản lý nắm giữ hành vi của các trình giữ chỗ chân trang slide bố cục, ngày-giờ, số trang và tất cả các trình giữ chỗ con.
type: docs
url: /vi/com.aspose.slides/layoutslideheaderfootermanager/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Tất cả các giao diện đã thực thi:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Đại diện cho quản lý nắm giữ hành vi của các placeholder chân trang, ngày-giờ, số trang của slide bố cục và tất cả các placeholder con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Thay đổi độ hiển thị của placeholder chân trang slide bố cục và tất cả các placeholder chân trang con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào master slide. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Thay đổi độ hiển thị của placeholder số trang slide bố cục và tất cả các placeholder số trang con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Thay đổi độ hiển thị của placeholder ngày-giờ slide bố cục và tất cả các placeholder ngày-giờ con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Đặt văn bản cho placeholder chân trang slide bố cục và tất cả các placeholder chân trang con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Đặt văn bản cho placeholder ngày-giờ slide bố cục và tất cả các placeholder ngày-giờ con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


Thay đổi độ hiển thị của placeholder chân trang slide bố cục và tất cả các placeholder chân trang con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder chân trang hiển thị, ngược lại - ẩn chúng. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Thay đổi độ hiển thị của placeholder số trang slide bố cục và tất cả các placeholder số trang con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder số trang hiển thị, ngược lại - ẩn chúng. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Thay đổi độ hiển thị của placeholder ngày-giờ slide bố cục và tất cả các placeholder ngày-giờ con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các placeholder ngày-giờ hiển thị, ngược lại - ẩn chúng. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


Đặt văn bản cho placeholder chân trang slide bố cục và tất cả các placeholder chân trang con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


Đặt văn bản cho placeholder ngày-giờ slide bố cục và tất cả các placeholder ngày-giờ con. Các placeholder con có nghĩa là các placeholder được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |