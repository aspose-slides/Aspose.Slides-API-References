---
title: IMasterNotesSlideHeaderFooterManager
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Đại diện cho trình quản lý chịu trách nhiệm hành vi của các trình giữ chỗ footer, ngày giờ, số trang của slide ghi chú chính và tất cả các trình giữ chỗ con.
type: docs
url: /vi/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Đại diện cho trình quản lý chịu trách nhiệm hành vi của các trình giữ chỗ footer, ngày-giờ, số trang của slide ghi chú chính và tất cả các trình giữ chỗ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide ghi chú phụ thuộc. Các slide ghi chú phụ thuộc sử dụng và phụ thuộc vào slide ghi chú chính.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ header của slide ghi chú chính và tất cả các trình giữ chỗ header con. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ header của slide ghi chú chính và tất cả các trình giữ chỗ header con. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ footer của slide ghi chú chính và tất cả các trình giữ chỗ footer con. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ số trang của slide ghi chú chính và tất cả các trình giữ chỗ số trang con. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ của slide ghi chú chính và tất cả các trình giữ chỗ ngày-giờ con. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ footer của slide ghi chú chính và tất cả các trình giữ chỗ footer con. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Đặt văn bản cho trình giữ chỗ ngày-giờ của slide ghi chú chính và tất cả các trình giữ chỗ ngày-giờ con. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ header của slide ghi chú chính và tất cả các trình giữ chỗ header con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide ghi chú phụ thuộc. Các slide ghi chú phụ thuộc sử dụng và phụ thuộc vào slide ghi chú chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ header hiển thị, ngược lại - ẩn chúng. |
### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Đặt văn bản cho trình giữ chỗ header của slide ghi chú chính và tất cả các trình giữ chỗ header con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide ghi chú phụ thuộc. Các slide ghi chú phụ thuộc sử dụng và phụ thuộc vào slide ghi chú chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản để đặt. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ footer của slide ghi chú chính và tất cả các trình giữ chỗ footer con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide ghi chú phụ thuộc. Các slide ghi chú phụ thuộc sử dụng và phụ thuộc vào slide ghi chú chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ footer hiển thị, ngược lại - ẩn chúng. |
### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ số trang của slide ghi chú chính và tất cả các trình giữ chỗ số trang con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide ghi chú phụ thuộc. Các slide ghi chú phụ thuộc sử dụng và phụ thuộc vào slide ghi chú chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ số trang hiển thị, ngược lại - ẩn chúng. |
### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Thay đổi khả năng hiển thị của trình giữ chỗ ngày-giờ của slide ghi chú chính và tất cả các trình giữ chỗ ngày-giờ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide ghi chú phụ thuộc. Các slide ghi chú phụ thuộc sử dụng và phụ thuộc vào slide ghi chú chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| isVisible | boolean | true - làm cho các trình giữ chỗ ngày-giờ hiển thị, ngược lại - ẩn chúng. |
### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Đặt văn bản cho trình giữ chỗ footer của slide ghi chú chính và tất cả các trình giữ chỗ footer con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide ghi chú phụ thuộc. Các slide ghi chú phụ thuộc sử dụng và phụ thuộc vào slide ghi chú chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản để đặt. |
### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Đặt văn bản cho trình giữ chỗ ngày-giờ của slide ghi chú chính và tất cả các trình giữ chỗ ngày-giờ con. Trình giữ chỗ con có nghĩa là các trình giữ chỗ được chứa trong các slide ghi chú phụ thuộc. Các slide ghi chú phụ thuộc sử dụng và phụ thuộc vào slide ghi chú chính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản để đặt. |