---
title: IBaseSlideHeaderFooterManager
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho trình quản lý giữ hành vi của các placeholder footer, ngày-giờ, số trang cho mọi loại slide.
type: docs
url: /vi/com.aspose.slides/ibaseslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Đại diện cho trình quản lý giữ hành vi của các placeholder footer, ngày-giờ, số trang cho mọi loại slide.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Lấy giá trị cho biết placeholder footer có tồn tại. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Lấy giá trị cho biết placeholder số trang có tồn tại. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Lấy giá trị cho biết placeholder ngày-giờ có tồn tại. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Thay đổi hiển thị placeholder footer của slide. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Thay đổi hiển thị placeholder số trang của slide. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Thay đổi hiển thị placeholder ngày-giờ của slide. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Đặt văn bản cho placeholder footer của slide. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Đặt văn bản cho placeholder ngày-giờ của slide. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


Lấy giá trị cho biết placeholder footer có tồn tại. Đọc boolean.

**Trả về:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


Lấy giá trị cho biết placeholder số trang có tồn tại. Đọc boolean.

**Trả về:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


Lấy giá trị cho biết placeholder ngày-giờ có tồn tại. Đọc boolean.

**Trả về:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


Thay đổi hiển thị placeholder footer của slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder footer hiển thị, ngược lại - ẩn nó. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


Thay đổi hiển thị placeholder số trang của slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder số trang hiển thị, ngược lại - ẩn nó. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


Thay đổi hiển thị placeholder ngày-giờ của slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho placeholder ngày-giờ hiển thị, ngược lại - ẩn nó. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


Đặt văn bản cho placeholder footer của slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


Đặt văn bản cho placeholder ngày-giờ của slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |