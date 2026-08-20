---
title: SmartArtShape
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn hình SmartArt
type: docs
url: /vi/com.aspose.slides/smartartshape/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tất cả các Interface đã triển khai:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Biểu diễn hình SmartArt
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShapeType()](#getShapeType--) | Trả về hoặc đặt loại preset hình học. |
| [setShapeType(int value)](#setShapeType-int-) | Trả về hoặc đặt loại preset hình học. |
| [getTextFrame()](#getTextFrame--) | Trả về văn bản của hình SmartArt. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Trả về hoặc đặt loại preset hình học. Lưu ý: khi thay đổi giá trị, tất cả các giá trị điều chỉnh sẽ được đặt lại về giá trị mặc định. Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Trả về:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Trả về hoặc đặt loại preset hình học. Lưu ý: khi thay đổi giá trị, tất cả các giá trị điều chỉnh sẽ được đặt lại về giá trị mặc định. Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Trả về văn bản của hình SmartArt. Chỉ-đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)