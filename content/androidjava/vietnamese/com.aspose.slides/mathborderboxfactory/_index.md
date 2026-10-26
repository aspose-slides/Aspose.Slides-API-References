---
title: MathBorderBoxFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo một hộp viền toán học
type: docs
url: /vi/com.aspose.slides/mathborderboxfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Cho phép tạo một hộp viền toán học

--------------------

Đối với tính tương thích COM
## Các hàm tạo

| Constructor | Description |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Phương thức

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Tạo một hộp viền toán học bằng cách áp dụng vào phần tử |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Tạo một hộp viền toán học bằng cách áp dụng vào phần tử |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Tạo một hộp viền toán học bằng cách áp dụng vào phần tử

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng hộp viền |

**Giá trị trả về:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - phần tử hộp viền mới
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Tạo một hộp viền toán học bằng cách áp dụng vào phần tử

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng hộp viền |
| hideTop | boolean | Ẩn cạnh trên |
| hideBottom | boolean | Ẩn cạnh dưới |
| hideLeft | boolean | Ẩn cạnh trái |
| hideRight | boolean | Ẩn cạnh phải |
| strikethroughHorizontal | boolean | Gạch ngang hộp viền |
| strikethroughVertical | boolean | Gạch dọc hộp viền |
| strikethroughBottomLeftToTopRight | boolean | Gạch chéo hộp viền từ góc dưới trái lên góc trên phải |
| strikethroughTopLeftToBottomRight | boolean | Gạch chéo hộp viền từ góc trên trái xuống góc dưới phải |

**Giá trị trả về:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - phần tử hộp viền mới