---
title: ShapeThumbnailBounds
second_title: Tham chiếu API Aspose.Slides cho Java
description: Liệt kê các loại giới hạn hình thu nhỏ.
type: docs
url: /vi/com.aspose.slides/shapethumbnailbounds/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Liệt kê các loại giới hạn hình thu nhỏ.

## Trường

| Trường | Mô tả |
| --- | --- |
| [Slide](#Slide) | Shape thumbnail will have the size equal to slide size. |
| [Shape](#Shape) | Shape thumbnail will have size equal to the shape bounds rectangle with taking into account shape outline settings. |
| [Appearance](#Appearance) | Shape thumbnail will have size equal to the shape appearance (in bounds of a slide). |
### Slide {#Slide}
```
public static final int Slide
```

Shape thumbnail sẽ có kích thước bằng kích thước slide. Vị trí shape sẽ được lưu lại.

### Shape {#Shape}
```
public static final int Shape
```

Shape thumbnail sẽ có kích thước bằng hình chữ nhật giới hạn shape, tính đến các cài đặt nét viền shape.

### Appearance {#Appearance}
```
public static final int Appearance
```

Shape thumbnail sẽ có kích thước bằng diện mạo shape (trong phạm vi slide). Có thể xảy ra trường hợp diện mạo shape không vừa với giới hạn shape. Ví dụ: xoay, nối miter của góc nhọn, hiệu ứng 3D, v.v.