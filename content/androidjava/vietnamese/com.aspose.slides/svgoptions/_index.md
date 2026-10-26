---
title: SVGOptions
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một tùy chọn SVG.
type: docs
url: /vi/com.aspose.slides/svgoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Biểu diễn một tùy chọn SVG.
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Khởi tạo một thể hiện mới của lớp SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Khởi tạo một thể hiện mới của lớp SVGOptions, chỉ định đối tượng bộ điều khiển nhúng liên kết. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu được xuất. |
| [getUseFrameSize()](#getUseFrameSize--) | Xác định xem khung văn bản có được bao gồm trong khu vực hiển thị hay không. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Xác định xem khung văn bản có được bao gồm trong khu vực hiển thị hay không. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Xác định có thực hiện việc xoay hình dạng được chỉ định khi hiển thị hay không. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Xác định có thực hiện việc xoay hình dạng được chỉ định khi hiển thị hay không. |
| [getVectorizeText()](#getVectorizeText--) | Xác định xem văn bản trên slide có được lưu dưới dạng đồ họa hay không. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Xác định xem văn bản trên slide có được lưu dưới dạng đồ họa hay không. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho việc raster hóa metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho việc raster hóa metafile. |
| [getDisable3DText()](#getDisable3DText--) | Xác định liệu văn bản 3D có bị tắt trong SVG hay không. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Xác định liệu văn bản 3D có bị tắt trong SVG hay không. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Vô hiệu hoá việc tách gradient FromCornerX và FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Vô hiệu hoá việc tách gradient FromCornerX và FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 không hỗ trợ xác định lề cho các dấu đánh dấu. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 không hỗ trợ xác định lề cho các dấu đánh dấu. |
| [getDefault()](#getDefault--) | Trả về cài đặt mặc định. |
| [getSimple()](#getSimple--) | Trả về cài đặt cho việc tạo tệp SVG đơn giản nhất và nhỏ nhất. |
| [getWYSIWYG()](#getWYSIWYG--) | Trả về cài đặt cho việc tạo tệp SVG chính xác nhất. |
| [getJpegQuality()](#getJpegQuality--) | Xác định chất lượng mã hóa JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Xác định chất lượng mã hóa JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Trả về và đặt một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Trả về và đặt một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. |
| [getPicturesCompression()](#getPicturesCompression--) | Biểu diễn mức độ nén hình ảnh |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Biểu diễn mức độ nén hình ảnh |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Cờ boolean cho biết các phần đã cắt có vẫn giữ lại trong tài liệu hay không. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Cờ boolean cho biết các phần đã cắt có vẫn giữ lại trong tài liệu hay không. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Xác định cách xử lý phông chữ được tải từ bên ngoài. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Xác định cách xử lý phông chữ được tải từ bên ngoài. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligatures hay không. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligatures hay không. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Khởi tạo một thể hiện mới của lớp SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Khởi tạo một thể hiện mới của lớp SVGOptions, chỉ định đối tượng bộ điều khiển nhúng liên kết.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Tham chiếu bộ điều khiển nhúng liên kết. |

--------------------

Link embedding controller là một đối tượng delegate chịu trách nhiệm quyết định liệu các tài nguyên (như hình ảnh) cần được nhúng hay tham chiếu như tài nguyên bên ngoài.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu được xuất. Chỉ đọc [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Xác định xem khung văn bản có được bao gồm trong khu vực hiển thị hay không. Đọc/ghi boolean. Giá trị mặc định là false.

**Trả về:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Xác định xem khung văn bản có được bao gồm trong khu vực hiển thị hay không. Đọc/ghi boolean. Giá trị mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Xác định có thực hiện việc xoay hình dạng được chỉ định khi hiển thị hay không. Đọc/ghi boolean. Giá trị mặc định là true.

**Trả về:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Xác định có thực hiện việc xoay hình dạng được chỉ định khi hiển thị hay không. Đọc/ghi boolean. Giá trị mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho việc raster hóa metafile. Đọc/ghi int.

**Trả về:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho việc raster hóa metafile. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Xác định liệu văn bản 3D có bị tắt trong SVG hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Xác định liệu văn bản 3D có bị tắt trong SVG hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Vô hiệu hoá việc tách gradient FromCornerX và FromCenter. Đọc/ghi boolean.

**Trả về:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Vô hiệu hoá việc tách gradient FromCornerX và FromCenter. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 không hỗ trợ xác định lề cho các dấu đánh dấu. Engine viết SVG của Aspose.Slides có giải pháp khắc phục vấn đề này: nó cắt phần cuối của đường có mũi tên, vì vậy đường không chồng lên các dấu đánh dấu. Tùy chọn này tắt hành vi đó. Đọc/ghi boolean.

**Trả về:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 không hỗ trợ xác định lề cho các dấu đánh dấu. Engine viết SVG của Aspose.Slides có giải pháp khắc phục vấn đề này: nó cắt phần cuối của đường có mũi tên, vì vậy đường không chồng lên các dấu đánh dấu. Tùy chọn này tắt hành vi đó. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Trả về cài đặt mặc định. Chỉ đọc [SVGOptions](../../com.aspose.slides/svgoptions).

**Trả về:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Trả về cài đặt cho việc tạo tệp SVG đơn giản nhất và nhỏ nhất. Chỉ đọc [SVGOptions](../../com.aspose.slides/svgoptions).

**Trả về:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Trả về cài đặt cho việc tạo tệp SVG chính xác nhất. Chỉ đọc [SVGOptions](../../com.aspose.slides/svgoptions).

**Trả về:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Xác định chất lượng mã hóa JPEG. Đọc/ghi int.

**Trả về:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Xác định chất lượng mã hóa JPEG. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Trả về và đặt một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. Đọc/ghi [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Trả về:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Trả về và đặt một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. Đọc/ghi [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Biểu diễn mức độ nén hình ảnh

**Trả về:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Biểu diễn mức độ nén hình ảnh

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Cờ boolean cho biết các phần đã cắt có vẫn giữ lại trong tài liệu hay không. Nếu true, các phần đã cắt sẽ bị xóa, nếu false chúng sẽ được tuần tự hóa trong tài liệu (có thể dẫn đến tệp lớn hơn).

**Trả về:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Cờ boolean cho biết các phần đã cắt có vẫn giữ lại trong tài liệu hay không. Nếu true, các phần đã cắt sẽ bị xóa, nếu false chúng sẽ được tuần tự hóa trong tài liệu (có thể dẫn đến tệp lớn hơn).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Xác định cách xử lý phông chữ được tải từ bên ngoài. Đọc/ghi [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Trả về:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Xác định cách xử lý phông chữ được tải từ bên ngoài. Đọc/ghi [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligatures hay không. Khi đặt thành true, ligatures sẽ bị tắt trong đầu ra đã render. Mặc định, thuộc tính này được đặt là false.

--------------------

> ```
> Ví dụ:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligatures hay không. Khi đặt thành true, ligatures sẽ bị tắt trong đầu ra đã render. Mặc định, thuộc tính này được đặt là false.

--------------------

> ```
> Ví dụ:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |