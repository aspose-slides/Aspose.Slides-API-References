---
title: ISVGOptions
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Đại diện cho các tùy chọn SVG.
type: docs
url: /vi/com.aspose.slides/isvgoptions/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Đại diện cho các tùy chọn SVG.
## Phương thức

| Method | Description |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Trả về hoặc thiết lập giới hạn độ phân giải thấp hơn cho raster hoá metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Trả về hoặc thiết lập giới hạn độ phân giải thấp hơn cho raster hoá metafile. |
| [getDisable3DText()](#getDisable3DText--) | Xác định liệu văn bản 3D có bị tắt trong SVG hay không. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Xác định liệu văn bản 3D có bị tắt trong SVG hay không. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Vô hiệu hoá việc chia tách gradient FromCornerX và FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Vô hiệu hoá việc chia tách gradient FromCornerX và FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 thiếu khả năng định nghĩa lề cho các marker. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 thiếu khả năng định nghĩa lề cho các marker. |
| [getJpegQuality()](#getJpegQuality--) | Xác định chất lượng mã hoá JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Xác định chất lượng mã hoá JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Trả về và thiết lập một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Trả về và thiết lập một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. |
| [getPicturesCompression()](#getPicturesCompression--) | Đại diện cho mức nén hình ảnh Read/write #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Đại diện cho mức nén hình ảnh Read/write #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Một cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Một cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. |
| [getUseFrameSize()](#getUseFrameSize--) | Xác định liệu khung văn bản có được bao gồm trong khu vực render hay không. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Xác định liệu khung văn bản có được bao gồm trong khu vực render hay không. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Xác định liệu thực hiện việc xoay hình dạng đã chỉ định khi render hay không. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Xác định liệu thực hiện việc xoay hình dạng đã chỉ định khi render hay không. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Xác định cách xử lý các phông chữ được tải từ bên ngoài. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Xác định cách xử lý các phông chữ được tải từ bên ngoài. |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lấy hoặc đặt giá trị cho biết văn bản có được render mà không sử dụng ligatures hay không. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lấy hoặc đặt giá trị cho biết văn bản có được render mà không sử dụng ligatures hay không. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Trả về hoặc thiết lập giới hạn độ phân giải thấp hơn cho raster hoá metafile. Đọc/ghi int.

**Trả về:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Trả về hoặc thiết lập giới hạn độ phân giải thấp hơn cho raster hoá metafile. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Xác định liệu văn bản 3D có bị tắt trong SVG hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Xác định liệu văn bản 3D có bị tắt trong SVG hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Vô hiệu hoá việc chia tách gradient FromCornerX và FromCenter. Đọc/ghi boolean.

**Trả về:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Vô hiệu hoá việc chia tách gradient FromCornerX và FromCenter. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 thiếu khả năng định nghĩa lề cho các marker. Aspose.Slides SVG writing engine có cách khắc phục vấn đề này: nó cắt phần cuối của đường có mũi tên, vì vậy đường không chồng lên marker. Tùy chọn này tắt hành vi đó. Đọc/ghi boolean.

**Trả về:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 thiếu khả năng định nghĩa lề cho các marker. Aspose.Slides SVG writing engine có cách khắc phục vấn đề này: nó cắt phần cuối của đường có mũi tên, vì vậy đường không chồng lên marker. Tùy chọn này tắt hành vi đó. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Xác định chất lượng mã hoá JPEG. Đọc/ghi int.

**Trả về:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Xác định chất lượng mã hoá JPEG. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Trả về và thiết lập một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. Đọc/ghi [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Trả về:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Trả về và thiết lập một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. Đọc/ghi [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Đại diện cho mức nén hình ảnh Read/write #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Trả về:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Đại diện cho mức nén hình ảnh Read/write #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Một cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. Nếu true, các phần đã cắt sẽ bị xóa, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn tới tệp lớn hơn) Đọc/ghi boolean.

**Trả về:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Một cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. Nếu true, các phần đã cắt sẽ bị xóa, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn tới tệp lớn hơn) Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Xác định liệu khung văn bản có được bao gồm trong khu vực render hay không. Đọc/ghi boolean. Giá trị mặc định là false.

**Trả về:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Xác định liệu khung văn bản có được bao gồm trong khu vực render hay không. Đọc/ghi boolean. Giá trị mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Xác định liệu thực hiện việc xoay hình dạng đã chỉ định khi render hay không. Đọc/ghi boolean. Giá trị mặc định là true.

**Trả về:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Xác định liệu thực hiện việc xoay hình dạng đã chỉ định khi render hay không. Đọc/ghi boolean. Giá trị mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Xác định cách xử lý các phông chữ được tải từ bên ngoài. Đọc/ghi [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Trả về:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Xác định cách xử lý các phông chữ được tải từ bên ngoài. Đọc/ghi [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất. Chỉ đọc [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Lấy hoặc đặt giá trị cho biết văn bản có được render mà không sử dụng ligatures hay không. Khi đặt thành true, ligatures sẽ bị tắt trong kết quả render. Mặc định, thuộc tính này được đặt là false.

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
public abstract void setDisableFontLigatures(boolean value)
```

Lấy hoặc đặt giá trị cho biết văn bản có được render mà không sử dụng ligatures hay không. Khi đặt thành true, ligatures sẽ bị tắt trong kết quả render. Mặc định, thuộc tính này được đặt là false.

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

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |