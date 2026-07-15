---
title: MathDelimiter
second_title: Aspose.Slides for Android qua Tham chiếu API Java
description: Xác định đối tượng dấu phân cách bao gồm các ký tự mở và đóng như ngoặc tròn, ngoặc nhọn, ngoặc vuông và thanh dọc, và một hoặc nhiều phần tử toán học bên trong được tách bằng một ký tự chỉ định.
type: docs
url: /vi/com.aspose.slides/mathdelimiter/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Xác định đối tượng dấu phân cách, bao gồm các ký tự mở và đóng (như ngoặc tròn, ngoặc nhọn, ngoặc vuông và thanh dọc), và một hoặc nhiều phần tử toán học bên trong, được tách bằng một ký tự chỉ định. Ví dụ: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Khởi tạo MathDelimiter với phần tử được chỉ định làm đối số cơ sở duy nhất |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getArguments()](#getArguments--) | Một hoặc nhiều phần tử toán học được tách bằng các ký tự dấu phân cách |
| [getBeginningCharacter()](#getBeginningCharacter--) | Ký tự bắt đầu của dấu phân cách xác định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Ký tự bắt đầu của dấu phân cách xác định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Ký tự ngăn cách của dấu phân cách xác định ký tự tách các đối số trong đối tượng dấu phân cách. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Ký tự ngăn cách của dấu phân cách xác định ký tự tách các đối số trong đối tượng dấu phân cách. |
| [getEndingCharacter()](#getEndingCharacter--) | Ký tự kết thúc của dấu phân cách xác định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Ký tự kết thúc của dấu phân cách xác định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để phù hợp với chiều cao của toán hạng. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để phù hợp với chiều cao của toán hạng. |
| [getDelimiterShape()](#getDelimiterShape--) | Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. |
| [delimit(char separatorCharacter)](#delimit-char-) | Tách các đối số bằng ký tự dấu phân cách đã chỉ định |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bao bọc một phần tử toán học bằng các ký tự được chỉ định như ngoặc tròn hoặc các ký tự khác như khung |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


Khởi tạo MathDelimiter với phần tử được chỉ định làm đối số cơ sở duy nhất

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cơ sở mà dấu phân cách được áp dụng. Có thể null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
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
public final char getBeginningCharacter()
```


Ký tự bắt đầu của dấu phân cách xác định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. Các dấu phân cách toán học là các ký tự bao bọc như ngoặc tròn, ngoặc vuông và ngoặc nhọn. Mặc định: '('.

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
public final void setBeginningCharacter(char value)
```


Ký tự bắt đầu của dấu phân cách xác định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. Các dấu phân cách toán học là các ký tự bao bọc như ngoặc tròn, ngoặc vuông và ngoặc nhọn. Mặc định: '('.

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
public final char getSeparatorCharacter()
```


Ký tự ngăn cách của dấu phân cách xác định ký tự tách các đối số trong đối tượng dấu phân cách. Mặc định: '|'.

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
public final void setSeparatorCharacter(char value)
```


Ký tự ngăn cách của dấu phân cách xác định ký tự tách các đối số trong đối tượng dấu phân cách. Mặc định: '|'.

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
public final char getEndingCharacter()
```


Ký tự kết thúc của dấu phân cách xác định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. Các dấu phân cách toán học là các ký tự bao bọc như ngoặc tròn, ngoặc vuông và ngoặc nhọn. Mặc định: ')'.

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
public final void setEndingCharacter(char value)
```


Ký tự kết thúc của dấu phân cách xác định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. Các dấu phân cách toán học là các ký tự bao bọc như ngoặc tròn, ngoặc vuông và ngoặc nhọn. Mặc định: ')'.

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
public final boolean getGrowToMatchOperandHeight()
```


Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để phù hợp với chiều cao của toán hạng. Giá trị mặc định là true

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
public final void setGrowToMatchOperandHeight(boolean value)
```


Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để phù hợp với chiều cao của toán hạng. Giá trị mặc định là true

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
public final int getDelimiterShape()
```


Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. Khi là MathDelimiterShape.Centered, các dấu phân cách được căn giữa quanh trục toán học của văn bản toán học và vẫn được điều chỉnh để vừa với toàn bộ chiều cao của nội dung. Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung.

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
public final void setDelimiterShape(int value)
```


Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. Khi là MathDelimiterShape.Centered, các dấu phân cách được căn giữa quanh trục toán học của văn bản toán học và vẫn được điều chỉnh để vừa với toàn bộ chiều cao của nội dung. Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung.

--------------------

> ```
> Ví dụ:
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
public final IMathDelimiter delimit(char separatorCharacter)
```


Tách các đối số bằng ký tự dấu phân cách đã chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| separatorCharacter | char | ký tự dấu phân cách |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Đối tượng này sau khi áp dụng ký tự dấu phân cách
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Bao bọc một phần tử toán học bằng các ký tự được chỉ định như ngoặc tròn hoặc các ký tự khác như khung

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| beginningCharacter | char | Ký tự bắt đầu (thường là ngoặc trái) |
| endingCharacter | char | Ký tự kết thúc (thường là ngoặc phải) |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Nếu beginningCharacter và endingCharacter là null, các thuộc tính tương ứng chỉ được gán giá trị và không tạo đối tượng mới (trả về thể hiện này). Ngược lại, trả về phần tử toán học mới kiểu Delimiter bao gồm các ký tự đã chỉ định làm khung và thể hiện này của [MathDelimiter](../../com.aspose.slides/mathdelimiter) được khung bên trong.
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