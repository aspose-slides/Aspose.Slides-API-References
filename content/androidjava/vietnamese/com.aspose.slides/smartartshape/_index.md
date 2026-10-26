---
title: SmartArtShape
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn hình dạng SmartArt
type: docs
url: /vi/com.aspose.slides/smartartshape/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Biểu diễn hình dạng SmartArt
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShapeType()](#getShapeType--) | Trả về hoặc thiết lập kiểu preset hình học. |
| [setShapeType(int value)](#setShapeType-int-) | Trả về hoặc thiết lập kiểu preset hình học. |
| [getTextFrame()](#getTextFrame--) | Trả về văn bản của hình dạng SmartArt. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Trả về hoặc thiết lập kiểu preset hình học. Lưu ý: khi thay đổi giá trị, tất cả các giá trị điều chỉnh sẽ được đặt lại về giá trị mặc định. Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Giá trị trả về:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Trả về hoặc thiết lập kiểu preset hình học. Lưu ý: khi thay đổi giá trị, tất cả các giá trị điều chỉnh sẽ được đặt lại về giá trị mặc định. Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Trả về văn bản của hình dạng SmartArt. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Giá trị trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)