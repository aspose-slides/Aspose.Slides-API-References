---
title: IMathDelimiter
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định đối tượng dấu phân cách bao gồm các ký tự mở và đóng như dấu ngoặc tròn, dấu ngoặc nhọn, dấu ngoặc vuông và dấu gạch đứng, và một hoặc nhiều phần tử toán học bên trong được phân tách bằng một ký tự xác định.
type: docs
url: /vi/com.aspose.slides/imathdelimiter/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Xác định đối tượng dấu phân cách, bao gồm các ký tự mở và đóng (như dấu ngoặc tròn, dấu ngoặc nhọn, dấu ngoặc vuông và dấu gạch đứng), và một hoặc nhiều phần tử toán học bên trong, được phân tách bằng một ký tự xác định. **Ví dụ:** (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getArguments()](#getArguments--) | Một hoặc nhiều phần tử toán học được phân tách bằng ký tự dấu phân cách |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character xác định ký tự dấu phân cách mở. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character xác định ký tự dấu phân cách mở. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character xác định ký tự phân tách các đối số trong đối tượng dấu phân cách. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character xác định ký tự phân tách các đối số trong đối tượng dấu phân cách. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character xác định ký tự dấu phân cách đóng. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character xác định ký tự dấu phân cách đóng. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, dấu phân cách mở rộng theo chiều dọc để khớp với chiều cao operand. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, dấu phân cách mở rộng theo chiều dọc để khớp với chiều cao operand. |
| [getDelimiterShape()](#getDelimiterShape--) | Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. |
| [delimit(char separatorCharacter)](#delimit-char-) | Phân tách các đối số bằng ký tự dấu phân cách đã chỉ định |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


Một hoặc nhiều phần tử toán học được phân tách bằng ký tự dấu phân cách

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Trả về:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```


Delimiter Beginning Character xác định ký tự dấu phân cách mở. Các dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc tròn, dấu ngoặc vuông và dấu ngoặc nhọn. Giá trị mặc định: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Trả về:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```


Delimiter Beginning Character xác định ký tự dấu phân cách mở. Các dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc tròn, dấu ngoặc vuông và dấu ngoặc nhọn. Giá trị mặc định: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```


Delimiter Separator Character xác định ký tự phân tách các đối số trong đối tượng dấu phân cách. Mặc định: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Trả về:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```


Delimiter Separator Character xác định ký tự phân tách các đối số trong đối tượng dấu phân cách. Mặc định: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```


Delimiter Ending Character xác định ký tự dấu phân cách đóng. Các dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc tròn, dấu ngoặc vuông và dấu ngoặc nhọn. Giá trị mặc định: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Trả về:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```


Delimiter Ending Character xác định ký tự dấu phân cách đóng. Các dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc tròn, dấu ngoặc vuông và dấu ngoặc nhọn. Giá trị mặc định: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, dấu phân cách mở rộng theo chiều dọc để khớp với chiều cao operand. Giá trị mặc định là true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Trả về:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, dấu phân cách mở rộng theo chiều dọc để khớp với chiều cao operand. Giá trị mặc định là true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```


Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. Khi là MathDelimiterShape.Centered, các dấu phân cách được căn giữa trục toán học của văn bản và vẫn được điều chỉnh để vừa với toàn bộ chiều cao nội dung. Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Trả về:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```


Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. Khi là MathDelimiterShape.Centered, các dấu phân cách được căn giữa trục toán học của văn bản và vẫn được điều chỉnh để vừa với toàn bộ chiều cao nội dung. Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Phân tách các đối số bằng ký tự dấu phân cách đã chỉ định

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| separatorCharacter | char | ký tự dấu phân cách |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Đối tượng này sau khi áp dụng ký tự dấu phân cách