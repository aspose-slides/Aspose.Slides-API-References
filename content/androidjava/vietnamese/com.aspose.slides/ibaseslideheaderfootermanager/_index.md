---
title: IBaseSlideHeaderFooterManager
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho trình quản lý giữ hành vi của các trình giữ chỗ footer, ngày-giờ và số trang cho mọi loại slide.
type: docs
url: /vi/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Đại diện cho trình quản lý giữ hành vi của các trình giữ chỗ footer, ngày-giờ và số trang cho mọi loại slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Lấy giá trị cho biết rằng có trình giữ chỗ footer. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Lấy giá trị cho biết rằng có trình giữ chỗ số trang. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Lấy giá trị cho biết rằng có trình giữ chỗ ngày-giờ. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ footer trên slide. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ số trang trên slide. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ trên slide. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ footer trên slide. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ ngày-giờ trên slide. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Lấy giá trị cho biết rằng có trình giữ chỗ footer. Đọc boolean.

**Trả về:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Lấy giá trị cho biết rằng có trình giữ chỗ số trang. Đọc boolean.

**Trả về:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Lấy giá trị cho biết rằng có trình giữ chỗ ngày-giờ. Đọc boolean.

**Trả về:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ footer trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho trình giữ chỗ footer hiển thị, ngược lại - ẩn nó. |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ số trang trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho trình giữ chỗ số trang hiển thị, ngược lại - ẩn nó. |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho trình giữ chỗ ngày-giờ hiển thị, ngược lại - ẩn nó. |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Đặt văn bản cho trình giữ chỗ footer trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Đặt văn bản cho trình giữ chỗ ngày-giờ trên slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đặt. |