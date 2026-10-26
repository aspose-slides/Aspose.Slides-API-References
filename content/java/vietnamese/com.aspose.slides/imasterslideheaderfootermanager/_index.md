---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides cho Tham chiếu API Java
description: Đại diện cho trình quản lý giữ hành vi của các trình giữ chỗ chân trang, ngày-giờ và số trang của slide chính và tất cả các trình giữ chỗ con.
type: docs
url: /vi/com.aspose.slides/imasterslideheaderfootermanager/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Đại diện cho trình quản lý giữ hành vi của các trình giữ chỗ chân trang slide chính, ngày-giờ, số trang và tất cả các trình giữ chỗ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào slide chính.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ chân trang slide chính và tất cả các trình giữ chỗ chân trang con. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ số trang slide chính và tất cả các trình giữ chỗ số trang con. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ slide chính và tất cả các trình giữ chỗ ngày-giờ con. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ chân trang slide chính và tất cả các trình giữ chỗ chân trang con. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ ngày-giờ slide chính và tất cả các trình giữ chỗ ngày-giờ con. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ chân trang slide chính và tất cả các trình giữ chỗ chân trang con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào slide chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ chân trang hiển thị, nếu không - ẩn chúng. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ số trang slide chính và tất cả các trình giữ chỗ số trang con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào slide chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ số trang hiển thị, nếu không - ẩn chúng. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ slide chính và tất cả các trình giữ chỗ ngày-giờ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào slide chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ ngày-giờ hiển thị, nếu không - ẩn chúng. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Đặt văn bản cho trình giữ chỗ chân trang slide chính và tất cả các trình giữ chỗ chân trang con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào slide chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Đặt văn bản cho trình giữ chỗ ngày-giờ slide chính và tất cả các trình giữ chỗ ngày-giờ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào slide chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |