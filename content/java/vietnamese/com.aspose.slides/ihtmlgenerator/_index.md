---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Html generator.
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
| [addText(String text)](#addText-java.lang.String-) | Thêm văn bản thường vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể HTML. |
| [addText(char[] text)](#addText-char---) | Thêm văn bản thường vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Thêm văn bản thường vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Đặt giá trị thuộc tính trong dấu ngoặc kép và thêm vào tệp html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Đặt giá trị thuộc tính trong dấu ngoặc kép và thêm vào tệp html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Đặt giá trị thuộc tính trong dấu ngoặc kép và thêm vào tệp html. |
| [getSlideImageSize()](#getSlideImageSize--) | Trả về kích thước hình ảnh slide. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Trả về đơn vị mà kích thước hình ảnh slide được chỉ định. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Trả về mã CSS của đơn vị mà kích thước hình ảnh slide được chỉ định. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Trả về chỉ mục của slide đã được render trước đó hoặc -1 nếu đang render slide đầu tiên. |
| [getSlideIndex()](#getSlideIndex--) | Trả về chỉ mục của slide đang được render. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Trả về chỉ mục của slide sẽ được render sau slide hiện tại hoặc -1 nếu đang render slide cuối cùng. |

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
| startIndex | int | Chỉ số bắt đầu của phần cần thêm. |
| length | int | Độ dài của phần cần thêm. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Thêm văn bản thường vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể HTML. Các dấu ngắt dòng và khoảng trắng không bị thay thế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần thêm. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Thêm văn bản thường vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể HTML. Các dấu ngắt dòng và khoảng trắng không bị thay thế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | char[] | Văn bản cần thêm. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Thêm văn bản thường vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể HTML. Các dấu ngắt dòng và khoảng trắng không bị thay thế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | char[] | Văn bản cần thêm. |
| startIndex | int | Chỉ số bắt đầu của phần cần thêm. |
| length | int | Độ dài của phần cần thêm. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Đặt giá trị thuộc tính trong dấu ngoặc kép và thêm vào tệp html.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String | Chuỗi giá trị thuộc tính. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Đặt giá trị thuộc tính trong dấu ngoặc kép và thêm vào tệp html.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char[] | Chuỗi giá trị thuộc tính. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Đặt giá trị thuộc tính trong dấu ngoặc kép và thêm vào tệp html.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char[] | Chuỗi giá trị thuộc tính. |
| startIndex | int | Chỉ số bắt đầu của phần cần thêm. |
| length | int | Độ dài của phần cần thêm. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

Trả về kích thước hình ảnh slide. Chỉ đọc java.awt.geom.Dimension2D.

**Giá trị trả về:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Trả về đơn vị mà kích thước hình ảnh slide được chỉ định. Chỉ đọc [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Giá trị trả về:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Trả về mã CSS của đơn vị mà kích thước hình ảnh slide được chỉ định. Chỉ đọc String.

**Giá trị trả về:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Trả về chỉ mục của slide đã được render trước đó hoặc -1 nếu đang render slide đầu tiên. Chỉ đọc int.

**Giá trị trả về:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Trả về chỉ mục của slide đang được render. Chỉ đọc int.

**Giá trị trả về:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Trả về chỉ mục của slide sẽ được render sau slide hiện tại hoặc -1 nếu đang render slide cuối cùng. Chỉ đọc int.

**Giá trị trả về:**
int