---
title: MathDelimiter
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định đối tượng dấu phân cách bao gồm các ký tự mở và đóng như dấu ngoặc, ngoặc nhọn, ngoặc vuông và dấu gạch dọc và một hoặc nhiều phần tử toán học bên trong, được ngăn cách bằng một ký tự xác định.
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

Xác định đối tượng dấu phân cách, bao gồm các ký tự mở và đóng (như dấu ngoặc đơn, ngoặc nhọn, ngoặc vuông và dấu gạch dọc), và một hoặc nhiều phần tử toán học bên trong, được ngăn cách bằng một ký tự xác định. Ví dụ: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Khởi tạo MathDelimiter với phần tử được chỉ định làm đối số cơ sở duy nhất |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getArguments()](#getArguments--) | Một hoặc nhiều phần tử toán học được ngăn cách bằng các ký tự phân cách |
| [getBeginningCharacter()](#getBeginningCharacter--) | Ký tự bắt đầu dấu phân cách chỉ định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Ký tự bắt đầu dấu phân cách chỉ định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Ký tự ngăn cách dấu phân cách chỉ định ký tự ngăn cách các đối số trong đối tượng dấu phân cách. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Ký tự ngăn cách dấu phân cách chỉ định ký tự ngăn cách các đối số trong đối tượng dấu phân cách. |
| [getEndingCharacter()](#getEndingCharacter--) | Ký tự kết thúc dấu phân cách chỉ định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Ký tự kết thúc dấu phân cách chỉ định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để khớp với chiều cao của toán hạng. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách sẽ mở rộng theo chiều dọc để khớp với chiều cao của toán hạng. |
| [getDelimiterShape()](#getDelimiterShape--) | Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. |
| [delimit(char separatorCharacter)](#delimit-char-) | Phân cách các đối số bằng ký tự dấu phân cách được chỉ định |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bao bọc một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cơ sở mà dấu phân cách được áp dụng. Có thể là null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Một hoặc nhiều phần tử toán học được ngăn cách bằng các ký tự phân cách

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

Ký tự bắt đầu dấu phân cách chỉ định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. Dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc, ngoặc vuông và ngoặc nhọn. Mặc định: '('.

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

Ký tự bắt đầu dấu phân cách chỉ định ký tự bắt đầu, hoặc ký tự mở của dấu phân cách. Dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc, ngoặc vuông và ngoặc nhọn. Mặc định: '('.

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

Ký tự ngăn cách dấu phân cách chỉ định ký tự ngăn cách các đối số trong đối tượng dấu phân cách. Mặc định: '|'.

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

Ký tự ngăn cách dấu phân cách chỉ định ký tự ngăn cách các đối số trong đối tượng dấu phân cách. Mặc định: '|'.

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

Ký tự kết thúc dấu phân cách chỉ định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. Dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc, ngoặc vuông và ngoặc nhọn. Mặc định: ')'.

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

Ký tự kết thúc dấu phân cách chỉ định ký tự kết thúc, hoặc ký tự đóng của dấu phân cách. Dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc, ngoặc vuông và ngoặc nhọn. Mặc định: ')'.

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
public final void setGrowToMatchOperandHeight(boolean value)
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
public final int getDelimiterShape()
```

Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. Khi là MathDelimiterShape.Centered, các dấu phân cách được căn giữa trục toán học của văn bản toán học và vẫn có thể được điều chỉnh để vừa với toàn bộ chiều cao của nội dung. Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung.

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

Xác định hình dạng của các dấu phân cách trong đối tượng dấu phân cách. Khi là MathDelimiterShape.Centered, các dấu phân cách được căn giữa trục toán học của văn bản toán học và vẫn có thể được điều chỉnh để vừa với toàn bộ chiều cao của nội dung. Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung.

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
public final IMathDelimiter delimit(char separatorCharacter)
```

Phân cách các đối số bằng ký tự dấu phân cách được chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| separatorCharacter | char | ký tự phân cách |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Đối tượng này sau khi áp dụng ký tự phân cách
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Bao bọc một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Nếu beginningCharacter và endingCharacter là null, các thuộc tính tương ứng chỉ được gán giá trị và không tạo đối tượng mới (trả về thể hiện này). Nếu không, trả về phần tử toán học mới loại Delimiter bao gồm các ký tự được chỉ định làm khung và thể hiện [MathDelimiter](../../com.aspose.slides/mathdelimiter) này được bao quanh bên trong.
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