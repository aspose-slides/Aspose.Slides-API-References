---
title: SVGOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các tùy chọn SVG.
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

Biểu diễn các tùy chọn SVG.
## Các hàm khởi tạo

| Constructor | Description |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Khởi tạo một thể hiện mới của lớp SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Khởi tạo một thể hiện mới của lớp SVGOptions, chỉ định đối tượng điều khiển nhúng liên kết. |
## Phương thức

| Method | Description |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. |
| [getUseFrameSize()](#getUseFrameSize--) | Xác định liệu khung văn bản có được bao gồm trong khu vực hiển thị hay không. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Xác định liệu khung văn bản có được bao gồm trong khu vực hiển thị hay không. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Xác định việc thực hiện hoặc không thực hiện việc xoay hình đã chỉ định khi hiển thị. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Xác định việc thực hiện hoặc không thực hiện việc xoay hình đã chỉ định khi hiển thị. |
| [getVectorizeText()](#getVectorizeText--) | Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho raster hoá metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho raster hoá metafile. |
| [getDisable3DText()](#getDisable3DText--) | Xác định liệu văn bản 3D có bị tắt trong SVG hay không. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Xác định liệu văn bản 3D có bị tắt trong SVG hay không. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Vô hiệu hoá việc chia tách gradient FromCornerX và FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Vô hiệu hoá việc chia tách gradient FromCornerX và FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 thiếu khả năng định nghĩa lề cho các dấu đánh dấu. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 thiếu khả năng định nghĩa lề cho các dấu đánh dấu. |
| [getDefault()](#getDefault--) | Trả về các cài đặt mặc định. |
| [getSimple()](#getSimple--) | Trả về các cài đặt cho việc tạo tệp SVG đơn giản nhất và nhỏ nhất. |
| [getWYSIWYG()](#getWYSIWYG--) | Trả về các cài đặt cho việc tạo tệp SVG chính xác nhất. |
| [getJpegQuality()](#getJpegQuality--) | Xác định chất lượng mã hoá JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Xác định chất lượng mã hoá JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Trả về và đặt một giao diện callback cho phép người dùng điều khiển việc chuyển đổi hình dạng. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Trả về và đặt một giao diện callback cho phép người dùng điều khiển việc chuyển đổi hình dạng. |
| [getPicturesCompression()](#getPicturesCompression--) | Biểu diễn mức độ nén hình ảnh |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Biểu diễn mức độ nén hình ảnh |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Xác định cách xử lý phông chữ được tải từ bên ngoài. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Xác định cách xử lý phông chữ được tải từ bên ngoài. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lấy hoặc đặt giá trị cho biết liệu văn bản có được hiển thị mà không sử dụng ligatures hay không. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lấy hoặc đặt giá trị cho biết liệu văn bản có được hiển thị mà không sử dụng ligatures hay không. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Khởi tạo một thể hiện mới của lớp SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Khởi tạo một thể hiện mới của lớp SVGOptions, chỉ định đối tượng điều khiển nhúng liên kết.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Tham chiếu tới đối tượng điều khiển nhúng liên kết. |

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Xác định liệu khung văn bản có được bao gồm trong khu vực hiển thị hay không. Read/write boolean. Giá trị mặc định là false.

**Trả về:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Xác định liệu khung văn bản có được bao gồm trong khu vực hiển thị hay không. Read/write boolean. Giá trị mặc định là false.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Xác định việc thực hiện hoặc không thực hiện việc xoay hình đã chỉ định khi hiển thị. Read/write boolean. Giá trị mặc định là true.

**Trả về:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Xác định việc thực hiện hoặc không thực hiện việc xoay hình đã chỉ định khi hiển thị. Read/write boolean. Giá trị mặc định là true.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. Read/write boolean.

**Trả về:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. Read/write boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho raster hoá metafile. Read/write int.

**Trả về:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho raster hoá metafile. Read/write int.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Xác định liệu văn bản 3D có bị tắt trong SVG hay không. Read/write boolean.

**Trả về:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Xác định liệu văn bản 3D có bị tắt trong SVG hay không. Read/write boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Vô hiệu hoá việc chia tách gradient FromCornerX và FromCenter. Read/write boolean.

**Trả về:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Vô hiệu hoá việc chia tách gradient FromCornerX và FromCenter. Read/write boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 thiếu khả năng định nghĩa lề cho các dấu đánh dấu. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean.

**Trả về:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 thiếu khả năng định nghĩa lề cho các dấu đánh dấu. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Trả về các cài đặt mặc định. Read-only [SVGOptions](../../com.aspose.slides/svgoptions).

**Trả về:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Trả về các cài đặt cho việc tạo tệp SVG đơn giản nhất và nhỏ nhất. Read-only [SVGOptions](../../com.aspose.slides/svgoptions).

**Trả về:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Trả về các cài đặt cho việc tạo tệp SVG chính xác nhất. Read-only [SVGOptions](../../com.aspose.slides/svgoptions).

**Trả về:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Xác định chất lượng mã hoá JPEG. Read/write int.

**Trả về:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Xác định chất lượng mã hoá JPEG. Read/write int.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Trả về và đặt một giao diện callback cho phép người dùng điều khiển việc chuyển đổi hình dạng. Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Trả về:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Trả về và đặt một giao diện callback cho phép người dùng điều khiển việc chuyển đổi hình dạng. Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Tham số:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. Nếu true các phần đã cắt sẽ bị loại bỏ, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến tệp lớn hơn)

**Trả về:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. Nếu true các phần đã cắt sẽ bị loại bỏ, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến tệp lớn hơn)

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Xác định cách xử lý phông chữ được tải từ bên ngoài. Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Trả về:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Xác định cách xử lý phông chữ được tải từ bên ngoài. Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Lấy hoặc đặt giá trị cho biết liệu văn bản có được hiển thị mà không sử dụng ligatures hay không. Khi đặt là true, ligatures sẽ bị tắt trong đầu ra đã render. Mặc định, thuộc tính này được đặt là false.

--------------------

> ```
> Example:
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

Lấy hoặc đặt giá trị cho biết liệu văn bản có được hiển thị mà không sử dụng ligatures hay không. Khi đặt là true, ligatures sẽ bị tắt trong đầu ra đã render. Mặc định, thuộc tính này được đặt là false.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |