---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho trình quản lý giữ hành vi của các trình giữ chỗ footer, ngày-giờ, số trang của slide bố cục và tất cả các trình giữ chỗ con.
type: docs
url: /vi/com.aspose.slides/layoutslideheaderfootermanager/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Tất cả giao diện được thực hiện:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Đại diện cho trình quản lý giữ hành vi của các trình giữ chỗ footer slide bố cục, ngày-giờ, số trang và tất cả các trình giữ chỗ con. Các trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ footer slide bố cục và tất cả các trình giữ chỗ footer con. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ số trang slide bố cục và tất cả các trình giữ chỗ số trang con. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ slide bố cục và tất cả các trình giữ chỗ ngày-giờ con. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ footer slide bố cục và tất cả các trình giữ chỗ footer con. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ ngày-giờ slide bố cục và tất cả các trình giữ chỗ ngày-giờ con. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


Thay đổi khả năng hiển thị của trình giữ chỗ footer slide bố cục và tất cả các trình giữ chỗ footer con. Các trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide chủ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ footer hiển thị, ngược lại - ẩn chúng. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Thay đổi khả năng hiển thị của trình giữ chỗ số trang slide bố cục và tất cả các trình giữ chỗ số trang con. Các trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ số trang hiển thị, ngược lại - ẩn chúng. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ slide bố cục và tất cả các trình giữ chỗ ngày-giờ con. Các trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ ngày-giờ hiển thị, ngược lại - ẩn chúng. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


Đặt văn bản cho trình giữ chỗ footer slide bố cục và tất cả các trình giữ chỗ footer con. Các trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


Đặt văn bản cho trình giữ chỗ ngày-giờ slide bố cục và tất cả các trình giữ chỗ ngày-giờ con. Các trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide phụ thuộc. Các slide phụ thuộc sử dụng và phụ thuộc vào slide bố cục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |