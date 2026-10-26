---
title: MasterSlideHeaderFooterManager
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho trình quản lý giữ hành vi của các trình giữ chỗ footer, ngày-giờ, số trang của master slide và tất cả các trình giữ chỗ con.
type: docs
url: /vi/com.aspose.slides/masterslideheaderfootermanager/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Đại diện cho trình quản lý giữ hành vi của các trình giữ chỗ footer, ngày-giờ, số trang của master slide và tất cả các trình giữ chỗ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào master slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Thay đổi tính hiển thị của trình giữ chỗ footer của master slide và tất cả các trình giữ chỗ footer con. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Thay đổi tính hiển thị của trình giữ chỗ số trang của master slide và tất cả các trình giữ chỗ số trang con. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Thay đổi tính hiển thị của trình giữ chỗ ngày-giờ của master slide và tất cả các trình giữ chỗ ngày-giờ con. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ footer của master slide và tất cả các trình giữ chỗ footer con. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ ngày-giờ của master slide và tất cả các trình giữ chỗ ngày-giờ con. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Thay đổi tính hiển thị của trình giữ chỗ footer của master slide và tất cả các trình giữ chỗ footer con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cộc phụ thuộc và các slide sử dụng và phụ thuộc vào master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ footer hiển thị, ngược lại - ẩn chúng. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Thay đổi tính hiển thị của trình giữ chỗ số trang của master slide và tất cả các trình giữ chỗ số trang con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ số trang hiển thị, ngược lại - ẩn chúng. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Thay đổi tính hiển thị của trình giữ chỗ ngày-giờ của master slide và tất cả các trình giữ chỗ ngày-giờ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ ngày-giờ hiển thị, ngược lại - ẩn chúng. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Đặt văn bản cho trình giữ chỗ footer của master slide và tất cả các trình giữ chỗ footer con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Đặt văn bản cho trình giữ chỗ ngày-giờ của master slide và tất cả các trình giữ chỗ ngày-giờ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |