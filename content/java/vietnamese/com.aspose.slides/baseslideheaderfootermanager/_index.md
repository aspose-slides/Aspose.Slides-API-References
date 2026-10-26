---
title: BaseSlideHeaderFooterManager
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho bộ quản lý chịu trách nhiệm hành vi của các trình giữ chỗ chân trang, ngày giờ và số trang cho mọi loại slide.
type: docs
url: /vi/com.aspose.slides/baseslideheaderfootermanager/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

Đại diện cho bộ quản lý chịu trách nhiệm hành vi của các trình giữ chỗ chân trang, ngày-giờ và số trang cho mọi loại slide.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Lấy giá trị cho biết rằng một trình giữ chỗ chân trang có mặt. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Lấy giá trị cho biết rằng một trình giữ chỗ số trang có mặt. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Lấy giá trị cho biết rằng một trình giữ chỗ ngày-giờ có mặt. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ chân trang trên slide. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ số trang trên slide. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ trên slide. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ chân trang trên slide. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ ngày-giờ trên slide. |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

Lấy giá trị cho biết rằng một trình giữ chỗ chân trang có mặt. Đọc kiểu boolean.

**Trả về:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

Lấy giá trị cho biết rằng một trình giữ chỗ số trang có mặt. Đọc kiểu boolean.

**Trả về:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

Lấy giá trị cho biết rằng một trình giữ chỗ ngày-giờ có mặt. Đọc kiểu boolean.

**Trả về:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ chân trang trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho trình giữ chỗ chân trang hiển thị, ngược lại - ẩn nó. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ số trang trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho trình giữ chỗ số trang hiển thị, ngược lại - ẩn nó. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho trình giữ chỗ ngày-giờ hiển thị, ngược lại - ẩn nó. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

Đặt văn bản cho trình giữ chỗ chân trang trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

Đặt văn bản cho trình giữ chỗ ngày-giờ trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |