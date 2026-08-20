---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Represents an adjustable drawing guide.
type: docs
url: /vi/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Biểu diễn một hướng dẫn vẽ có thể điều chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOrientation()](#getOrientation--) | Trả về hoặc đặt hướng của hướng dẫn vẽ. |
| [setOrientation(byte value)](#setOrientation-byte-) | Trả về hoặc đặt hướng của hướng dẫn vẽ. |
| [getPosition()](#getPosition--) | Trả về hoặc đặt vị trí của hướng dẫn vẽ tính bằng điểm từ góc trên, trái của slide. |
| [setPosition(float value)](#setPosition-float-) | Trả về hoặc đặt vị trí của hướng dẫn vẽ tính bằng điểm từ góc trên, trái của slide. |
| [getColor()](#getColor--) | Trả về hoặc đặt màu của hướng dẫn vẽ. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Trả về hoặc đặt màu của hướng dẫn vẽ. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


Trả về hoặc đặt hướng của hướng dẫn vẽ. Đọc/ghi [Orientation](../../com.aspose.slides/orientation).

**Trả về:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


Trả về hoặc đặt hướng của hướng dẫn vẽ. Đọc/ghi [Orientation](../../com.aspose.slides/orientation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Trả về hoặc đặt vị trí của hướng dẫn vẽ tính bằng điểm từ góc trên, trái của slide. Đọc/ghi float.

--------------------

Phạm vi giá trị điển hình là từ 0 đến chiều cao slide đối với hướng dẫn ngang và từ 0 đến chiều rộng slide đối với hướng dẫn dọc.

**Trả về:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Trả về hoặc đặt vị trí của hướng dẫn vẽ tính bằng điểm từ góc trên, trái của slide. Đọc/ghi float.

--------------------

Phạm vi giá trị điển hình là từ 0 đến chiều cao slide đối với hướng dẫn ngang và từ 0 đến chiều rộng slide đối với hướng dẫn dọc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


Trả về hoặc đặt màu của hướng dẫn vẽ. Đọc/ghi java.awt.Color.

**Trả về:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Trả về hoặc đặt màu của hướng dẫn vẽ. Đọc/ghi java.awt.Color.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.Color |  |