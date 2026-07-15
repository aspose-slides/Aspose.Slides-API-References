---
title: ShapeElement
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một phần của hình dạng có cùng đặc tính đường viền và độ đầy.
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

Biểu diễn một phần của hình dạng có cùng đặc tính đường viền và độ đầy.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParentShape()](#getParentShape--) | Trả về một Shape_PPT cho phần tử đã được tạo. |
| [getPathPoints()](#getPathPoints--) | Lấy một mảng các điểm xác định hình học của đường dẫn của phần tử. |
| [getPathTypes()](#getPathTypes--) | Lấy một mảng các giá trị byte xác định loại của mỗi điểm trong đường dẫn của phần tử. |
| [getFillSource()](#getFillSource--) | Trả về thông tin về cách điền một phần tử. |
| [getStrokeSource()](#getStrokeSource--) | Trả về thông tin về cách tô viền một phần tử. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Trả về một Shape_PPT cho phần tử đã được tạo. Chỉ đọc [Shape](../../com.aspose.slides/shape).

**Trả về:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Lấy một mảng các điểm xác định hình học của đường dẫn của phần tử.

**Trả về:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Lấy một mảng các giá trị byte xác định loại của mỗi điểm trong đường dẫn của phần tử.

**0** Cho biết điểm là điểm bắt đầu của một hình.

**1** Cho biết điểm là một trong hai đầu của một đường thẳng.

**3** Cho biết điểm là đầu mút hoặc điểm điều khiển của một spline Bézier bậc ba.

**7** Che dấu tất cả các bit ngoại trừ ba bit cấp thấp, các bit này chỉ ra loại điểm.

**16** Xác định rằng đoạn tương ứng là nét đứt.

**32** Xác định rằng điểm là một ký hiệu.

**128** Xác định rằng điểm là điểm cuối cùng trong một đường con đóng (hình).

**129** Cho biết một điểm dữ liệu vừa là đầu mút đoạn đường thẳng vừa là điểm cuối cùng của một đường con đóng.

**Trả về:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Trả về thông tin về cách điền một phần tử. Chỉ đọc [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Trả về:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Trả về thông tin về cách tô viền một phần tử. Chỉ đọc [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Trả về:**
byte