---
title: ShapeThumbnailBounds
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: การนับประเภทของขอบเขตรูปย่อของรูปร่าง.
type: docs
url: /th/com.aspose.slides/shapethumbnailbounds/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

การนับประเภทของขอบเขตรูปย่อของรูปร่าง.
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Slide](#Slide) | Shape thumbnail จะมีขนาดเท่ากับขนาด slide. |
| [Shape](#Shape) | Shape thumbnail จะมีขนาดเท่ากับ shape bounds rectangle พร้อมคำนึงถึง shape outline settings. |
| [Appearance](#Appearance) | Shape thumbnail จะมีขนาดเท่ากับ shape appearance (ในขอบเขตของ slide). |

### สไลด์ {#Slide}
```
public static final int Slide
```

Shape thumbnail จะมีขนาดเท่ากับขนาด slide. ตำแหน่ง Shape จะถูกบันทึก.

### รูปร่าง {#Shape}
```
public static final int Shape
```

Shape thumbnail จะมีขนาดเท่ากับ shape bounds rectangle พร้อมคำนึงถึง shape outline settings.

### ลักษณะ {#Appearance}
```
public static final int Appearance
```

Shape thumbnail จะมีขนาดเท่ากับ shape appearance (ในขอบเขตของ slide). อาจมีกรณีที่ shape appearance ไม่พอดีกับ shape bounds. เช่น rotation, miter join ของ acute angle, เอฟเฟกต์ 3D, เป็นต้น.