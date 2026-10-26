---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Cho phép tạo một hộp viền toán học
type: docs
url: /vi/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Cho phép tạo một hộp viền toán học

--------------------

Đối với khả năng tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Tạo một hộp viền toán học bằng cách áp dụng vào phần tử |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Tạo một hộp viền toán học bằng cách áp dụng vào phần tử |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Tạo một hộp viền toán học bằng cách áp dụng vào phần tử

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng hộp viền |

**Giá trị trả về:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - phần tử hộp viền mới
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Tạo một hộp viền toán học bằng cách áp dụng vào phần tử

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng hộp viền |
| hideTop | boolean | Ẩn cạnh trên |
| hideBottom | boolean | Ẩn cạnh dưới |
| hideLeft | boolean | Ẩn cạnh trái |
| hideRight | boolean | Ẩn cạnh phải |
| strikethroughHorizontal | boolean | Gạch ngang hộp viền theo chiều ngang |
| strikethroughVertical | boolean | Gạch ngang hộp viền theo chiều dọc |
| strikethroughBottomLeftToTopRight | boolean | Gạch ngang hộp viền từ dưới trái lên trên phải |
| strikethroughTopLeftToBottomRight | boolean | Gạch ngang hộp viền từ trên trái xuống dưới phải |

**Giá trị trả về:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - phần tử hộp viền mới