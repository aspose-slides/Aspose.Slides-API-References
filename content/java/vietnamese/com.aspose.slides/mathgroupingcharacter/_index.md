---
title: MathGroupingCharacter
second_title: Tham khảo API Aspose.Slides cho Java
description: Xác định một ký hiệu nhóm ở trên hoặc dưới một biểu thức, thường để làm nổi bật mối quan hệ giữa các phần tử
type: docs
url: /vi/com.aspose.slides/mathgroupingcharacter/
---
**Kế thừa:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**  
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Chỉ định một ký hiệu nhóm ở trên hoặc dưới một biểu thức, thường để làm nổi bật mối quan hệ giữa các phần tử

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Khởi tạo một thể hiện mới của lớp MathGroupingCharacter với ký tự nhóm mặc định U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Khởi tạo một thể hiện mới của lớp MathGroupingCharacter. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getCharacter()](#getCharacter--) | Ký tự nhóm Giá trị mặc định: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Ký tự nhóm Giá trị mặc định: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Vị trí của ký tự nhóm. |
| [setPosition(int value)](#setPosition-int-) | Vị trí của ký tự nhóm. |
| [getVerticalJustification()](#getVerticalJustification--) | Canh lề dọc của ký tự nhóm. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Canh lề dọc của ký tự nhóm. |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

Khởi tạo một thể hiện mới của lớp MathGroupingCharacter với ký tự nhóm mặc định U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cơ sở mà thanh được áp dụng |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Khởi tạo một thể hiện mới của lớp MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cơ sở mà thanh được áp dụng |
| character | char | Ký tự nhóm |
| position | int | Vị trí của ký tự nhóm |
| verticalJustification | int | Canh lề dọc của ký tự nhóm |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Đối số cơ sở

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Ký tự nhóm Giá trị mặc định: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dấu ngoặc dưới
> ```

**Trả về:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Ký tự nhóm Giá trị mặc định: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dấu ngoặc dưới
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Vị trí của ký tự nhóm. Mặc định: Dưới

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setPosition(MathTopBotPositions.Top);
> ```

**Trả về:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Vị trí của ký tự nhóm. Mặc định: Dưới

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setPosition(MathTopBotPositions.Top);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

Canh lề dọc của ký tự nhóm. Xác định cách căn chỉnh đối tượng so với đường cơ sở. Ví dụ, khi ký tự nhóm ở trên đối tượng, Canh lề dọc Top có nghĩa là phía trên của đối tượng nằm trên đường cơ sở; khi Canh lề dọc được đặt là Bottom, phần dưới của đối tượng nằm trên đường cơ sở. Mặc định: Bottom cho Position=Top và Top cho Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Trả về:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

Canh lề dọc của ký tự nhóm. Xác định cách căn chỉnh đối tượng so với đường cơ sở. Ví dụ, khi ký tự nhóm ở trên đối tượng, Canh lề dọc Top có nghĩa là phía trên của đối tượng nằm trên đường cơ sở; khi Canh lề dọc được đặt là Bottom, phần dưới của đối tượng nằm trên đường cơ sở. Mặc định: Bottom cho Position=Top và Top cho Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Thuộc tính ký tự điều khiển

**Trả về:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps