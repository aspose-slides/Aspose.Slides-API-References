---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Trình tạo HTML.
type: docs
url: /vi/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Trình tạo HTML.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Thêm văn bản HTML đã định dạng. |
| [addHtml(char[] html)](#addHtml-char---) | Thêm văn bản HTML đã định dạng. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Thêm văn bản HTML đã định dạng. |
| [addText(String text)](#addText-java.lang.String-) | Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. |
| [addText(char[] text)](#addText-char---) | Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Đặt dấu ngoặc kép cho giá trị thuộc tính và thêm nó vào tệp html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Đặt dấu ngoặc kép cho giá trị thuộc tính và thêm nó vào tệp html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Đặt dấu ngoặc kép cho giá trị thuộc tính và thêm nó vào tệp html. |
| [getSlideImageSize()](#getSlideImageSize--) | Trả về kích thước ảnh slide. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Trả về đơn vị mà kích thước ảnh slide được chỉ định. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Trả về mã CSS của đơn vị mà kích thước ảnh slide được chỉ định. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Trả về chỉ số của slide đã được render trước đó hoặc -1 nếu đang render slide đầu tiên. |
| [getSlideIndex()](#getSlideIndex--) | Trả về chỉ số của slide đang được render. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Trả về chỉ số của một slide sẽ được render sau slide hiện tại hoặc -1 nếu đang render slide cuối cùng. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Thêm văn bản HTML đã định dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| html | java.lang.String | Văn bản cần thêm. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Thêm văn bản HTML đã định dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| html | char[] | Văn bản cần thêm. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Thêm văn bản HTML đã định dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| html | char[] | Văn bản cần thêm. |
| startIndex | int | Chỉ mục bắt đầu của phần cần thêm. |
| length | int | Độ dài của phần cần thêm. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. Các ký tự xuống dòng và khoảng trắng không được thay thế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần thêm. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. Các ký tự xuống dòng và khoảng trắng không được thay thế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | char[] | Văn bản cần thêm. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Thêm văn bản thuần vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. Các ký tự xuống dòng và khoảng trắng không được thay thế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | char[] | Văn bản cần thêm. |
| startIndex | int | Chỉ mục bắt đầu của phần cần thêm. |
| length | int | Độ dài của phần cần thêm. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Đặt dấu ngoặc kép cho giá trị thuộc tính và thêm nó vào tệp html.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String | Chuỗi giá trị thuộc tính. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Đặt dấu ngoặc kép cho giá trị thuộc tính và thêm nó vào tệp html.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char[] | Chuỗi giá trị thuộc tính. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Đặt dấu ngoặc kép cho giá trị thuộc tính và thêm nó vào tệp html.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char[] | Chuỗi giá trị thuộc tính. |
| startIndex | int | Chỉ mục bắt đầu của phần cần thêm. |
| length | int | Độ dài của phần cần thêm. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

Trả về kích thước ảnh slide. Chỉ đọc [SizeF](../../com.aspose.slides.android/sizef).

**Trả về:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Trả về đơn vị mà kích thước ảnh slide được chỉ định. Chỉ đọc [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Trả về:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Trả về mã CSS của đơn vị mà kích thước ảnh slide được chỉ định. Chỉ đọc String.

**Trả về:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Trả về chỉ số của slide đã được render trước đó hoặc -1 nếu slide đầu tiên đang được render. Chỉ đọc int.

**Trả về:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Trả về chỉ số của slide đang được render. Chỉ đọc int.

**Trả về:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Trả về chỉ số của một slide sẽ được render sau slide hiện tại hoặc -1 nếu đang render slide cuối cùng. Chỉ đọc int.

**Trả về:**
int