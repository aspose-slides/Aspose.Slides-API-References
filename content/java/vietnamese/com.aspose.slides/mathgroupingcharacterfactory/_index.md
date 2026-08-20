---
title: MathGroupingCharacterFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo ký tự nhóm toán học
type: docs
url: /vi/com.aspose.slides/mathgroupingcharacterfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện đã triển khai:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Cho phép tạo ký tự nhóm toán học

--------------------

Để tương thích COM
## Phương thức khởi tạo

| Phương thức khởi tạo | Mô tả |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Tạo một ký tự nhóm toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng ký tự nhóm |
| character | char | ký tự nhóm |
| position | int | vị trí của ký tự nhóm |
| verticalJustification | int | căn dọc |

**Giá trị trả về:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - phần tử ký tự nhóm mới
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Tạo một ký tự nhóm toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng ký tự nhóm |

**Giá trị trả về:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - phần tử ký tự nhóm mới