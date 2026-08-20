---
title: IMathDelimiter
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định đối tượng dấu phân cách bao gồm các ký tự mở và đóng như dấu ngoặc, ngoặc nhọn, ngoặc vuông và dấu gạch đứng, và một hoặc nhiều phần tử toán học bên trong được tách bằng một ký tự chỉ định.
type: docs
url: /vi/com.aspose.slides/imathdelimiter/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Xác định đối tượng dấu phân cách, bao gồm các ký tự mở và đóng (chẳng hạn như dấu ngoặc, dấu ngoặc nhọn, dấu ngoặc vuông và dấu gạch đứng), và một hoặc nhiều phần tử toán học bên trong, được tách bằng một ký tự chỉ định. Ví dụ: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getArguments()](#getArguments--) | Một hoặc nhiều phần tử toán học được tách bằng các ký tự dấu phân cách |
| [getBeginningCharacter()](#getBeginningCharacter--) | Ký tự Đầu dấu phân cách chỉ định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Ký tự Đầu dấu phân cách chỉ định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Ký tự Phân cách Đấu dấu chỉ định ký tự tách các đối số trong đối tượng dấu phân cách. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Ký tự Phân cách Đấu dấu chỉ định ký tự tách các đối số trong đối tượng dấu phân cách. |
| [getEndingCharacter()](#getEndingCharacter--) | Ký tự Cuối dấu phân cách chỉ định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Ký tự Cuối dấu phân cách chỉ định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để khớp với chiều cao của toán hạng. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để khớp với chiều cao của toán hạng. |
| [getDelimiterShape()](#getDelimiterShape--) | Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. |
| [delimit(char separatorCharacter)](#delimit-char-) | Tách các đối số bằng ký tự dấu phân cách được chỉ định |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


Một hoặc nhiều phần tử toán học được tách bằng các ký tự dấu phân cách

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


Ký tự Đầu dấu phân cách chỉ định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. Các dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc, dấu ngoặc vuông và dấu ngoặc nhọn. Giá trị mặc định: '('.

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


Ký tự Đầu dấu phân cách chỉ định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. Các dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc, dấu ngoặc vuông và dấu ngoặc nhọn. Giá trị mặc định: '('.

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


Ký tự Phân cách Đấu dấu chỉ định ký tự tách các đối số trong đối tượng dấu phân cách. Mặc định: '|'.

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


Ký tự Phân cách Đấu dấu chỉ định ký tự tách các đối số trong đối tượng dấu phân cách. Mặc định: '|'.

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


Ký tự Cuối dấu phân cách chỉ định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. Các dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc, dấu ngoặc vuông và dấu ngoặc nhọn. Giá trị mặc định: ')'.

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


Ký tự Cuối dấu phân cách chỉ định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. Các dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc, dấu ngoặc vuông và dấu ngoặc nhọn. Giá trị mặc định: ')'.

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


Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để khớp với chiều cao của toán hạng. Giá trị mặc định là true

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


Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để khớp với chiều cao của toán hạng. Giá trị mặc định là true

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


Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. Khi là MathDelimiterShape.Centered, các dấu phân cách được căn giữa quanh trục toán học của văn bản toán học và vẫn được điều chỉnh để phù hợp với toàn bộ chiều cao của nội dung. Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung.

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


Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. Khi là MathDelimiterShape.Centered, các dấu phân cách được căn giữa quanh trục toán học của văn bản toán học và vẫn được điều chỉnh để phù hợp với toàn bộ chiều cao của nội dung. Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung.

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


Tách các đối số bằng ký tự dấu phân cách được chỉ định

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