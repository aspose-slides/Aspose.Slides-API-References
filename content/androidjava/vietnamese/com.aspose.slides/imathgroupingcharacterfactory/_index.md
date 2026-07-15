---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo ký tự nhóm toán học
type: docs
url: /vi/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Cho phép tạo ký tự nhóm toán học

--------------------

Đối với tính tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Tạo một ký tự nhóm toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng ký tự nhóm |
| character | char | ký tự nhóm |
| position | int | vị trí của ký tự nhóm |
| verticalJustification | int | căn dọc |

**Trả về:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - phần tử ký tự nhóm mới
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Tạo một ký tự nhóm toán học

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng ký tự nhóm |

**Trả về:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - phần tử ký tự nhóm mới