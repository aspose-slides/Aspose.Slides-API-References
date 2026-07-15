---
title: IPortionFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Lớp này chứa các thuộc tính định dạng phần văn bản.
type: docs
url: /vi/com.aspose.slides/iportionformat/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Lớp này chứa các thuộc tính định dạng phần văn bản. Không giống như [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), tất cả các thuộc tính của lớp này có thể ghi.

--------------------

Lớp này được dùng để trả về và thao tác các thuộc tính định dạng phần văn bản được xác định cho phần cụ thể. Điều này có nghĩa là không có kế thừa được áp dụng khi lấy giá trị, vì vậy trong phần lớn các trường hợp bạn sẽ nhận được các giá trị có nghĩa "không xác định".

Để lấy các giá trị tham số định dạng hiệu quả bao gồm cả kế thừa, bạn cần sử dụng phương thức [getEffective](../../com.aspose.slides/iportionformat\#getEffective) mà trả về một thể hiện [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Trả về hoặc đặt định danh dấu trang. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Trả về hoặc đặt định danh dấu trang. |
| [getSmartTagClean()](#getSmartTagClean--) | Xác định xem thẻ thông minh có nên bị xóa không. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Xác định xem thẻ thông minh có nên bị xóa không. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng phần hiệu quả với kế thừa đã được áp dụng. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Trả về hoặc đặt định danh dấu trang. Đọc/ghi String.

**Trả về:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```


Trả về hoặc đặt định danh dấu trang. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Xác định xem thẻ thông minh có nên bị xóa không. Không áp dụng kế thừa. Đọc/ghi boolean.

**Trả về:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```


Xác định xem thẻ thông minh có nên bị xóa không. Không áp dụng kế thừa. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```


Lấy dữ liệu định dạng phần hiệu quả với kế thừa đã được áp dụng.

**Trả về:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Một [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).