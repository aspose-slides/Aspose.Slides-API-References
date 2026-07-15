---
title: IMathGroupingCharacter
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định một ký hiệu nhóm ở trên hoặc dưới một biểu thức, thường để làm nổi bật mối quan hệ giữa các phần tử
type: docs
url: /vi/com.aspose.slides/imathgroupingcharacter/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Xác định một ký hiệu nhóm ở trên hoặc dưới một biểu thức, thường để làm nổi bật mối quan hệ giữa các phần tử

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getCharacter()](#getCharacter--) | Giá trị mặc định của ký tự nhóm: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Giá trị mặc định của ký tự nhóm: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Vị trí của ký tự nhóm. |
| [setPosition(int value)](#setPosition-int-) | Vị trí của ký tự nhóm. |
| [getVerticalJustification()](#getVerticalJustification--) | Cân chỉnh dọc của ký tự nhóm. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Cân chỉnh dọc của ký tự nhóm. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract char getCharacter()
```

Giá trị mặc định của ký tự nhóm: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract void setCharacter(char value)
```

Giá trị mặc định của ký tự nhóm: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract int getPosition()
```

Vị trí của ký tự nhóm. Mặc định: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Trả về:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Vị trí của ký tự nhóm. Mặc định: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Cân chỉnh dọc của ký tự nhóm. Xác định cách căn chỉnh đối tượng so với đường cơ sở. Ví dụ, khi ký tự nhóm ở trên đối tượng, VerticalJustification của Top có nghĩa là phần trên của đối tượng nằm trên đường cơ sở; khi VerticalJustification được đặt thành Bottom, phần dưới của đối tượng nằm trên đường cơ sở. Mặc định: Bottom cho Position=Top, và Top cho Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Trả về:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Cân chỉnh dọc của ký tự nhóm. Xác định cách căn chỉnh đối tượng so với đường cơ sở. Ví dụ, khi ký tự nhóm ở trên đối tượng, VerticalJustification của Top có nghĩa là phần trên của đối tượng nằm trên đường cơ sở; khi VerticalJustification được đặt thành Bottom, phần dưới của đối tượng nằm trên đường cơ sở. Mặc định: Bottom cho Position=Top, và Top cho Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |