---
title: ShapeElement
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một phần của hình dạng với cùng các thuộc tính đường viền và tô màu.
type: docs
url: /vi/com.aspose.slides/shapeelement/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Biểu diễn một phần của hình dạng có cùng các thuộc tính đường viền và tô màu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParentShape()](#getParentShape--) | Trả về một Shape\_PPT cho đó phần tử được tạo. |
| [getPathPoints()](#getPathPoints--) | Lấy một mảng các điểm xác định hình học của đường dẫn phần tử. |
| [getPathTypes()](#getPathTypes--) | Lấy một mảng các giá trị byte chỉ định loại của mỗi điểm trong đường dẫn phần tử. |
| [getFillSource()](#getFillSource--) | Trả về thông tin về cách tô một phần tử. |
| [getStrokeSource()](#getStrokeSource--) | Trả về thông tin về cách vẽ viền cho một phần tử. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


Trả về một Shape\_PPT cho đó phần tử được tạo. Chỉ đọc [Shape](../../com.aspose.slides/shape).

**Trả về:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```


Lấy một mảng các điểm xác định hình học của đường dẫn phần tử.

**Trả về:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


Lấy một mảng các giá trị byte chỉ định loại của mỗi điểm trong đường dẫn phần tử.

**0** Chỉ ra rằng điểm là điểm bắt đầu của một hình.

**1** Chỉ ra rằng điểm là một trong hai đầu mút của một đường thẳng.

**3** Chỉ ra rằng điểm là đầu mút hoặc điểm điều khiển của một spline Bezier bậc ba.

**7** Mặt nạ tất cả các bit ngoại trừ ba bit thấp, chỉ ra loại điểm.

**16** Chỉ ra rằng đoạn tương ứng là đoạn gạch ngang.

**32** Chỉ ra rằng điểm là một dấu.

**128** Chỉ ra rằng điểm là điểm cuối cùng trong một đường phụ đóng (hình).

**129** Chỉ ra một điểm dữ liệu vừa là đầu mút đoạn đường thẳng vừa là điểm cuối cùng của một đường phụ đóng.

**Trả về:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


Trả về thông tin về cách tô một phần tử. Chỉ đọc [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Trả về:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


Trả về thông tin về cách vẽ viền cho một phần tử. Chỉ đọc [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Trả về:**
byte