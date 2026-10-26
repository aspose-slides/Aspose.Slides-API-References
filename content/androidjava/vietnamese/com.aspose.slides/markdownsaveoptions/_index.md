---
title: MarkdownSaveOptions
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho các tùy chọn kiểm soát cách bản trình bày được lưu dưới dạng markdown.
type: docs
url: /vi/com.aspose.slides/markdownsaveoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Đại diện cho các tùy chọn kiểm soát cách bản trình bày được lưu dưới dạng markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Hàm khởi tạo. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getExportType()](#getExportType--) | Xác định đặc tả markdown để chuyển đổi bản trình bày. |
| [setExportType(int value)](#setExportType-int-) | Xác định đặc tả markdown để chuyển đổi bản trình bày. |
| [getBasePath()](#getBasePath--) | Xác định đường dẫn cơ sở nơi tài liệu kèm tài nguyên sẽ được lưu. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Xác định đường dẫn cơ sở nơi tài liệu kèm tài nguyên sẽ được lưu. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Xác định tên thư mục để lưu hình ảnh. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Xác định tên thư mục để lưu hình ảnh. |
| [getNewLineType()](#getNewLineType--) | Xác định liệu tài liệu được tạo ra có nên có các dòng mới \\r(Macintosh) \\n(Unix) hoặc \\r\\n(Windows) hay không. |
| [setNewLineType(int value)](#setNewLineType-int-) | Xác định liệu tài liệu được tạo ra có nên có các dòng mới \\r(Macintosh) \\n(Unix) hoặc \\r\\n(Windows) hay không. |
| [getShowComments()](#getShowComments--) | Xác định liệu tài liệu được tạo ra có hiển thị bình luận hay không. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Xác định liệu tài liệu được tạo ra có hiển thị bình luận hay không. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định liệu tài liệu được tạo ra có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định liệu tài liệu được tạo ra có bao gồm các slide ẩn hay không. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Xác định liệu tài liệu được tạo ra có hiển thị số của mỗi slide hay không. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Xác định liệu tài liệu được tạo ra có hiển thị số của mỗi slide hay không. |
| [getFlavor()](#getFlavor--) | Xác định đặc tả markdown để chuyển đổi bản trình bày. |
| [setFlavor(int value)](#setFlavor-int-) | Xác định đặc tả markdown để chuyển đổi bản trình bày. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Lấy hoặc đặt chuỗi định dạng được sử dụng cho tiêu đề số slide trong đầu ra Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Lấy hoặc đặt chuỗi định dạng được sử dụng cho tiêu đề số slide trong đầu ra Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Xác định cách xử lý các ký tự khoảng trắng thường lặp lại trong quá trình xuất Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Xác định cách xử lý các ký tự khoảng trắng thường lặp lại trong quá trình xuất Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Nếu đặt là true, sẽ loại bỏ các dòng trống hoặc chỉ chứa khoảng trắng khỏi đầu ra Markdown cuối cùng. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Nếu đặt là true, sẽ loại bỏ các dòng trống hoặc chỉ chứa khoảng trắng khỏi đầu ra Markdown cuối cùng. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Xảy ra cho mỗi hình ảnh không phải SVG (bitmap hoặc metafile) trong quá trình xuất Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Xảy ra cho mỗi hình ảnh SVG trong quá trình xuất Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Hàm khởi tạo.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


Xác định đặc tả markdown để chuyển đổi bản trình bày. Mặc định là TextOnly.

**Trả về:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


Xác định đặc tả markdown để chuyển đổi bản trình bày. Mặc định là TextOnly.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


Xác định đường dẫn cơ sở nơi tài liệu kèm tài nguyên sẽ được lưu. Mặc định là thư mục hiện tại của ứng dụng.

**Trả về:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


Xác định đường dẫn cơ sở nơi tài liệu kèm tài nguyên sẽ được lưu. Mặc định là thư mục hiện tại của ứng dụng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


Xác định tên thư mục để lưu hình ảnh. Mặc định là Images.

**Trả về:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


Xác định tên thư mục để lưu hình ảnh. Mặc định là Images.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


Xác định liệu tài liệu được tạo ra có nên có các dòng mới \\r(Macintosh) \\n(Unix) hoặc \\r\\n(Windows) hay không. Mặc định là Unix.

**Trả về:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


Xác định liệu tài liệu được tạo ra có nên có các dòng mới \\r(Macintosh) \\n(Unix) hoặc \\r\\n(Windows) hay không. Mặc định là Unix.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


Xác định liệu tài liệu được tạo ra có hiển thị bình luận hay không. Mặc định là false.

**Trả về:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


Xác định liệu tài liệu được tạo ra có hiển thị bình luận hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Xác định liệu tài liệu được tạo ra có bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Xác định liệu tài liệu được tạo ra có bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


Xác định liệu tài liệu được tạo ra có hiển thị số của mỗi slide hay không. Mặc định là false.

**Trả về:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


Xác định liệu tài liệu được tạo ra có hiển thị số của mỗi slide hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


Xác định đặc tả markdown để chuyển đổi bản trình bày. Mặc định là Multi-markdown.

**Trả về:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


Xác định đặc tả markdown để chuyển đổi bản trình bày. Mặc định là Multi-markdown.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


Lấy hoặc đặt chuỗi định dạng được sử dụng cho tiêu đề số slide trong đầu ra Markdown. Định dạng phải bao gồm ký tự giữ chỗ "\{0\}", sẽ được thay thế bằng chỉ số slide khi xuất. Ví dụ: "\# Slide \{0\}" sẽ cho ra "\# Slide 1", "\# Slide 2", v.v.

**Trả về:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


Lấy hoặc đặt chuỗi định dạng được sử dụng cho tiêu đề số slide trong đầu ra Markdown. Định dạng phải bao gồm ký tự giữ chỗ "\{0\}", sẽ được thay thế bằng chỉ số slide khi xuất. Ví dụ: "\# Slide \{0\}" sẽ cho ra "\# Slide 1", "\# Slide 2", v.v.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


Xác định cách xử lý các ký tự khoảng trắng thường lặp lại trong quá trình xuất Markdown. Thuộc tính này xác định liệu các khoảng trắng liên tiếp có: - được giữ nguyên như ký tự khoảng trắng thường, - được xen kẽ giữa khoảng trắng thường và thực thể không ngắt dòng (�), - hoặc được thay thế hoàn toàn (sau ký tự đầu tiên) bằng ký tự không ngắt dòng để giữ căn chỉnh trực quan trong đầu ra Markdown. Giá trị mặc định là [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Trả về:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


Xác định cách xử lý các ký tự khoảng trắng thường lặp lại trong quá trình xuất Markdown. Thuộc tính này xác định liệu các khoảng trắng liên tiếp có: - được giữ nguyên như ký tự khoảng trắng thường, - được xen kẽ giữa khoảng trắng thường và thực thể không ngắt dòng (�), - hoặc được thay thế hoàn toàn (sau ký tự đầu tiên) bằng ký tự không ngắt dòng để giữ căn chỉnh trực quan trong đầu ra Markdown. Giá trị mặc định là [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


Nếu đặt là true, sẽ loại bỏ các dòng trống hoặc chỉ chứa khoảng trắng khỏi đầu ra Markdown cuối cùng. Mặc định là false.

**Trả về:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


Nếu đặt là true, sẽ loại bỏ các dòng trống hoặc chỉ chứa khoảng trắng khỏi đầu ra Markdown cuối cùng. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


Xảy ra cho mỗi hình ảnh không phải SVG (bitmap hoặc metafile) trong quá trình xuất Markdown. Cho phép tùy chỉnh cách lưu và tham chiếu hình ảnh. Nếu không xử lý, hình ảnh sẽ được lưu cục bộ với liên kết tương đối.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Sự kiện lưu hình ảnh Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


Xảy ra cho mỗi hình ảnh SVG trong quá trình xuất Markdown. Cho phép ghi đè việc lưu và tạo liên kết mặc định. Nếu không xử lý, SVG sẽ được lưu cục bộ với liên kết tương đối.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Sự kiện lưu hình ảnh SVG Markdown. |