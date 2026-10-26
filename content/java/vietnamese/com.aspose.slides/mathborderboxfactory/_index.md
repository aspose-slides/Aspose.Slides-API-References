---
title: MathBorderBoxFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo một hộp viền toán học
type: docs
url: /vi/com.aspose.slides/mathborderboxfactory/
---
**Kế thừa:**  
java.lang.Object

**Tất cả các giao diện được thực thi:**  
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)  
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Cho phép tạo một hộp viền toán học

--------------------

Để tương thích COM
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |

## Methods

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Tạo một hộp viền toán học bằng cách áp dụng cho phần tử |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Tạo một hộp viền toán học bằng cách áp dụng cho phần tử |

### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

Tạo một hộp viền toán học bằng cách áp dụng cho phần tử

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng hộp viền |

**Giá trị trả về:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - phần tử hộp viền mới

### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Tạo một hộp viền toán học bằng cách áp dụng cho phần tử

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng hộp viền |
| hideTop | boolean | Ẩn cạnh trên |
| hideBottom | boolean | Ẩn cạnh dưới |
| hideLeft | boolean | Ẩn cạnh trái |
| hideRight | boolean | Ẩn cạnh phải |
| strikethroughHorizontal | boolean | Gạch chéo ngang hộp viền |
| strikethroughVertical | boolean | Gạch chéo dọc hộp viền |
| strikethroughBottomLeftToTopRight | boolean | Gạch chéo hộp viền từ góc dưới-trái tới trên-phải |
| strikethroughTopLeftToBottomRight | boolean | Gạch chéo hộp viền từ góc trên-trái tới dưới-phải |

**Giá trị trả về:**  
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - phần tử hộp viền mới