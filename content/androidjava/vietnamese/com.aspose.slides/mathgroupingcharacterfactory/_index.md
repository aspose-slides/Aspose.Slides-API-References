---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cho phép tạo ký tự nhóm toán học
type: docs
url: /vi/com.aspose.slides/mathgroupingcharacterfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Cho phép tạo ký tự nhóm toán học

--------------------

Để tương thích COM
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Tạo một ký tự nhóm toán học |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Tạo một ký tự nhóm toán học |
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