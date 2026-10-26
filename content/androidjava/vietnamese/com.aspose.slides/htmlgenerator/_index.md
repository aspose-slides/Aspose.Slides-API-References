---
title: HtmlGenerator
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Trình tạo HTML.
type: docs
url: /vi/com.aspose.slides/htmlgenerator/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Trình tạo HTML.
## Phương thức

| Method | Description |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Thêm văn bản HTML đã định dạng. |
| [addHtml(char[] html)](#addHtml-char---) | Thêm văn bản HTML đã định dạng. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Thêm văn bản HTML đã định dạng. |
| [addText(String text)](#addText-java.lang.String-) | Thêm văn bản thuần túy vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. |
| [addText(char[] text)](#addText-char---) | Thêm văn bản thuần túy vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Thêm văn bản thuần túy vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Bao ngoặc giá trị thuộc tính và thêm vào tệp html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Bao ngoặc giá trị thuộc tính và thêm vào tệp html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Bao ngoặc giá trị thuộc tính và thêm vào tệp html. |
| [getSlideImageSize()](#getSlideImageSize--) | Trả về kích thước hình ảnh slide. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Trả về đơn vị mà kích thước hình ảnh slide được chỉ định. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Trả về mã CSS của đơn vị mà kích thước hình ảnh slide được chỉ định. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Trả về chỉ mục của slide đã được render trước đó hoặc -1 nếu slide đầu tiên đang được render. |
| [getSlideIndex()](#getSlideIndex--) | Trả về chỉ mục của slide hiện đang được render. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Trả về chỉ mục của slide sẽ được render sau slide hiện tại hoặc -1 nếu đang render slide cuối cùng. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


Thêm văn bản HTML đã định dạng.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| html | java.lang.String | Văn bản cần thêm. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


Thêm văn bản HTML đã định dạng.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| html | char[] | Văn bản cần thêm. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


Thêm văn bản HTML đã định dạng.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| html | char[] | Văn bản cần thêm. |
| startIndex | int | Chỉ mục bắt đầu của phần cần thêm. |
| length | int | Độ dài của phần cần thêm. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


Thêm văn bản thuần túy vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. Các ký tự ngắt dòng và khoảng trắng không bị thay thế.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần thêm. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


Thêm văn bản thuần túy vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. Các ký tự ngắt dòng và khoảng trắng không bị thay thế.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | char[] | Văn bản cần thêm. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


Thêm văn bản thuần túy vào các tệp html, thay thế các ký tự đặc biệt bằng thực thể html. Các ký tự ngắt dòng và khoảng trắng không bị thay thế.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | char[] | Văn bản cần thêm. |
| startIndex | int | Chỉ mục bắt đầu của phần cần thêm. |
| length | int | Độ dài của phần cần thêm. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


Bao ngoặc giá trị thuộc tính và thêm vào tệp html.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Chuỗi giá trị thuộc tính. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


Bao ngoặc giá trị thuộc tính và thêm vào tệp html.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char[] | Chuỗi giá trị thuộc tính. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


Bao ngoặc giá trị thuộc tính và thêm vào tệp html.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char[] | Chuỗi giá trị thuộc tính. |
| startIndex | int | Chỉ mục bắt đầu của phần cần thêm. |
| length | int | Độ dài của phần cần thêm. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```


Trả về kích thước hình ảnh slide. Chỉ đọc [SizeF](../../com.aspose.slides.android/sizef).

**Returns:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```


Trả về đơn vị mà kích thước hình ảnh slide được chỉ định. Chỉ đọc [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Returns:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


Trả về mã CSS của đơn vị mà kích thước hình ảnh slide được chỉ định. Chỉ đọc String.

**Returns:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


Trả về chỉ mục của slide đã được render trước đó hoặc -1 nếu slide đầu tiên đang được render. Chỉ đọc int.

**Returns:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Trả về chỉ mục của slide hiện đang được render. Chỉ đọc int.

**Returns:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


Trả về chỉ mục của slide sẽ được render sau slide hiện tại hoặc -1 nếu đang render slide cuối cùng. Chỉ đọc int.

**Returns:**
int