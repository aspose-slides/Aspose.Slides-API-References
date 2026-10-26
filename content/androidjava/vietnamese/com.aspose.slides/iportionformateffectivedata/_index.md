---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đối tượng bất biến chứa các thuộc tính định dạng phần văn bản hiệu quả.
type: docs
url: /vi/com.aspose.slides/iportionformateffectivedata/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Đối tượng bất biến chứa các thuộc tính định dạng phần văn bản hiệu quả.

--------------------

Giao diện này được sử dụng cùng với giao diện [IPortionFormat](../../com.aspose.slides/iportionformat) để trả về các giá trị định dạng hiệu quả với kế thừa được áp dụng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Trả về định danh dấu trang. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Trả về siêu liên kết được định nghĩa cho cú nhấp chuột. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Trả về siêu liên kết được định nghĩa cho di chuột. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Trả về định danh dấu trang. Chỉ đọc String.

**Trả về:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

Trả về siêu liên kết được định nghĩa cho cú nhấp chuột. Chỉ đọc [IHyperlink](../../com.aspose.slides/ihyperlink).

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```

Trả về siêu liên kết được định nghĩa cho di chuột. Chỉ đọc [IHyperlink](../../com.aspose.slides/ihyperlink).

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink)