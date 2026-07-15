---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho trình quản lý chịu trách nhiệm hành vi của các trình giữ chỗ chân trang, ngày-giờ, số trang trên slide chủ và tất cả các trình giữ chỗ con.
type: docs
url: /vi/com.aspose.slides/imasterslideheaderfootermanager/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Đại diện cho trình quản lý chịu trách nhiệm hành vi của trình giữ chỗ chân trang, ngày-giờ, số trang trên slide chủ và tất cả các trình giữ chỗ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trên các slide bố cục phụ thuộc và các slide phụ thuộc. Các slide bố cục phụ thuộc và các slide sử dụng và phụ thuộc vào slide chủ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes master slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes master slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes master slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to master slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to master slide date-time placeholder and all child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Changes master slide footer placeholder and all child footer placeholders visibility. Child placeholders mean placeholders are contained on depending layout slides and depending slides. Depending layout slides and slides use and depend on master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ chân trang hiển thị, ngược lại - ẩn chúng. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Changes master slide page number placeholder and all child page number placeholders visibility. Child placeholders mean placeholders are contained on depending layout slides and depending slides. Depending layout slides and slides use and depend on master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ số trang hiển thị, ngược lại - ẩn chúng. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Changes master slide date-time placeholder and all child date-time placeholders visibility. Child placeholders mean placeholders are contained on depending layout slides and depending slides. Depending layout slides and slides use and depend on master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ ngày-giờ hiển thị, ngược lại - ẩn chúng. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Sets text to master slide footer placeholder and all child footer placeholders. Child placeholders mean placeholders are contained on depending layout slides and depending slides. Depending layout slides and slides use and depend on master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Sets text to master slide date-time placeholder and all child date-time placeholders. Child placeholders mean placeholders are contained on depending layout slides and depending slides. Depending layout slides and slides use and depend on master slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |