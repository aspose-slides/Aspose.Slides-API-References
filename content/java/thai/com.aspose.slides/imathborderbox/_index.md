---
title: IMathBorderBox
second_title: Aspose.Slides สำหรับ Java API Reference
description: วาดกรอบสี่เหลี่ยมหรือกรอบรูปแบบอื่น ๆ รอบ IMathElement.
type: docs
url: /th/com.aspose.slides/imathborderbox/
---
**ทั้งหมดที่ทำตามอินเทอร์เฟซ:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

วาดกรอบสี่เหลี่ยมหรือกรอบรูปแบบอื่น ๆ รอบ IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getHideTop()](#getHideTop--) | ซ่อนขอบด้านบน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านบนของกล่องกรอบ |
| [setHideTop(boolean value)](#setHideTop-boolean-) | ซ่อนขอบด้านบน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านบนของกล่องกรอบ |
| [getHideBottom()](#getHideBottom--) | ซ่อนขอบด้านล่าง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านล่างของกล่องกรอบ |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | ซ่อนขอบด้านล่าง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านล่างของกล่องกรอบ |
| [getHideLeft()](#getHideLeft--) | ซ่อนขอบด้านซ้าย (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านซ้ายของกล่องกรอบ |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | ซ่อนขอบด้านซ้าย (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านซ้ายของกล่องกรอบ |
| [getHideRight()](#getHideRight--) | ซ่อนขอบด้านขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านขวาของกล่องกรอบ |
| [setHideRight(boolean value)](#setHideRight-boolean-) | ซ่อนขอบด้านขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านขวาของกล่องกรอบ |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | เส้นขีดฆิดแนวนอน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดฆิดแนวนอน |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | เส้นขีดฆิดแนวนอน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดฆิดแนวนอน |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | เส้นขีดฆิดแนวตั้ง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดฆิดแนวตั้ง |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | เส้นขีดฆิดแนวตั้ง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดฆิดแนวตั้ง |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | เส้นขีดฆิดจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นคือ false) |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | เส้นขีดฆิดจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นคือ false) |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | เส้นขีดฆิดจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นคือ false) |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | เส้นขีดฆิดจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นคือ false) |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**คืนค่า:**  
[IMathElement](../../com.aspose.slides/imathelement)

### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

ซ่อนขอบด้านบน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านบนของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**คืนค่า:**  
boolean

### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

ซ่อนขอบด้านบน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านบนของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

ซ่อนขอบด้านล่าง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านล่างของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```


**คืนค่า:**  
boolean

### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

ซ่อนขอบด้านล่าง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านล่างของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

ซ่อนขอบด้านซ้าย (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านซ้ายของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**คืนค่า:**  
boolean

### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

ซ่อนขอบด้านซ้าย (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านซ้ายของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

ซ่อนขอบด้านขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**คืนค่า:**  
boolean

### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

ซ่อนขอบด้านขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

เส้นขีดฆิดแนวนอน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดฆิดแนวนอน

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**คืนค่า:**  
boolean

### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

เส้นขีดฆิดแนวนอน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดฆิดแนวนอน

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

เส้นขีดฆิดแนวตั้ง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดฆิดแนวตั้ง

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**คืนค่า:**  
boolean

### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

เส้นขีดฆิดแนวตั้ง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดฆิดแนวตั้ง

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

เส้นขีดฆิดจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นทแยงมุมจากมุมล่างซ้ายไปมุมบนขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**คืนค่า:**  
boolean

### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

เส้นขีดฆิดจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นทแยงมุมจากมุมล่างซ้ายไปมุมบนขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

เส้นขีดฆิดจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นทแยงมุมจากมุมบนซ้ายไปมุมล่างขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**คืนค่า:**  
boolean

### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

เส้นขีดฆิดจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นทแยงมุมจากมุมบนซ้ายไปมุมล่างขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |