---
title: MathElementBase
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Lớp cơ sở cho IMathElement với việc triển khai một số phương thức chung cho tất cả các lớp kế thừa. Chỉ dùng nội bộ.
type: docs
url: /vi/com.aspose.slides/mathelementbase/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được thực thi:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Lớp cơ sở cho IMathElement với việc triển khai một số phương thức chung cho tất cả các lớp kế thừa. Chỉ dùng nội bộ. Lớp kế thừa phải là IMathElement.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Trả về đối tượng Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Kết hợp một phần tử toán học và tạo một khối toán học |
| [join(String mathText)](#join-java.lang.String-) | Kết hợp một văn bản toán học và tạo một khối toán học |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [divide(String denominator)](#divide-java.lang.String-) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số được chỉ định |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số được chỉ định |
| [enclose()](#enclose--) | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bao quanh một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Lấy một hàm của đối số, sử dụng đối tượng này làm tên hàm |
| [function(String functionArgument)](#function-java.lang.String-) | Lấy một hàm của đối số, sử dụng đối tượng này làm tên hàm |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số và đối số bổ sung đã chỉ định |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số và đối số bổ sung đã chỉ định |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Tạo chỉ số dưới |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Tạo chỉ số dưới |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Tạo chỉ số trên |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Tạo chỉ số trên |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Tạo chỉ số dưới và chỉ số trên ở phía bên phải |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Tạo chỉ số dưới và chỉ số trên ở phía bên trái |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Xác định căn bậc toán học của độ bậc đã cho từ đối số được chỉ định. |
| [radical(String degree)](#radical-java.lang.String-) | Xác định căn bậc toán học của độ bậc đã cho từ đối số được chỉ định. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Lấy giới hạn trên |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Lấy giới hạn trên |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Lấy giới hạn dưới |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Lấy giới hạn dưới |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo một toán tử N-ary |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Tạo một toán tử N-ary |
| [toMathArray()](#toMathArray--) | Đặt vào một mảng dọc |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Lấy tích phân |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Lấy tích phân |
| [integral(int integralType)](#integral-int-) | Lấy tích phân không có giới hạn |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Lấy tích phân |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Lấy tích phân |
| [accent(char accentCharacter)](#accent-char-) | Đặt dấu nhấn (một ký tự ở trên phần tử này) |
| [overbar()](#overbar--) | Đặt một thanh ở trên phần tử này |
| [underbar()](#underbar--) | Đặt một thanh ở dưới phần tử này |
| [group()](#group--) | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [toBorderBox()](#toBorderBox--) | Đặt phần tử này vào một hộp viền |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Đặt phần tử này vào một hộp viền |
| [toBox()](#toBox--) | Đặt phần tử này vào một hộp phi thị (nhóm logic) được dùng để gom các thành phần của một phương trình hoặc các đoạn văn toán học khác. |
| [getChildren()](#getChildren--) | Lấy các phần tử con |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Giá trị trả về:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Kết hợp một phần tử toán học và tạo một khối toán học

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cần được kết hợp |

**Giá trị trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - Một IMathBlock mới chứa đối tượng này và đối số đã chỉ định

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Kết hợp một văn bản toán học và tạo một khối toán học

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | Văn bản toán học cần được kết hợp |

**Giá trị trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - Một IMathBlock mới chứa đối tượng này và đối số đã chỉ định

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Tạo một phân số với tử số này và mẫu số được chỉ định

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu số |

**Giá trị trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số mới

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Tạo một phân số với tử số này và mẫu số được chỉ định

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| denominator | java.lang.String | Mẫu số |

**Giá trị trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số mới

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Tạo một phân số loại đã chỉ định với tử số này và mẫu số được chỉ định

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu số |
| fractionType | int | Kiểu phân số: Bar, NoBar, Skewed, Linear |

**Giá trị trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số mới

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Tạo một phân số loại đã chỉ định với tử số này và mẫu số được chỉ định

--------------------

> ```
> Ví dụ:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| denominator | java.lang.String | Mẫu số |
| fractionType | int | Kiểu phân số: Bar, NoBar, Skewed, Linear |

**Giá trị trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số mới

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Bao quanh một phần tử toán học bằng dấu ngoặc đơn

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Giá trị trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Phần tử toán học loại [IMathDelimiter](../../com.aspose.slides/imathdelimiter) bao gồm dấu ngoặc

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Bao quanh một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| beginningCharacter | char | Ký tự đầu (thường là dấu ngoặc trái) |
| endingCharacter | char | Ký tự cuối (thường là dấu ngoặc phải) |

**Giá trị trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Phần tử toán học loại [IMathDelimiter](../../com.aspose.slides/imathdelimiter) bao gồm các ký tự đã chỉ định làm khung

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Lấy một hàm của đối số, sử dụng đối tượng này làm tên hàm

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Đối số của hàm |

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Lấy một hàm của đối số, sử dụng đối tượng này làm tên hàm

--------------------

> ```
> Ví dụ:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionArgument | java.lang.String | Đối số của hàm |

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số

--------------------

> ```
> Ví dụ:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Tên hàm |

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số

--------------------

> ```
> Ví dụ:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionName | java.lang.String | Tên hàm |

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | int | Một trong các kiểu hàm một đối số phổ biến |

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số và đối số bổ sung đã chỉ định

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Trả về logarit của 'x' với cơ số '5'
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | int | Một trong các kiểu hàm hai đối số phổ biến: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Đối số bổ sung tùy thuộc vào kiểu hàm |

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số và đối số bổ sung đã chỉ định

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Trả về logarit của 'x' với cơ số '5'
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | int | Một trong các kiểu hàm hai đối số phổ biến: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Đối số bổ sung tùy thuộc vào kiểu hàm |

**Giá trị trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Tạo chỉ số dưới

--------------------

> ```
> Ví dụ:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số dưới (chỉ số thấp bên phải) |

**Giá trị trả về:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Phần tử toán học mới loại [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Tạo chỉ số dưới

--------------------

> ```
> Ví dụ:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| subscript | java.lang.String | Chỉ số dưới (chỉ số thấp bên phải) |

**Giá trị trả về:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Phần tử toán học mới loại [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Tạo chỉ số trên

--------------------

> ```
> Ví dụ:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số trên (chỉ số cao bên phải) |

**Giá trị trả về:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Phần tử toán học mới loại [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Tạo chỉ số trên

--------------------

> ```
> Ví dụ:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| superscript | java.lang.String | Chỉ số trên (chỉ số cao bên phải) |

**Giá trị trả về:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Phần tử toán học mới loại [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Tạo chỉ số dưới và chỉ số trên ở phía bên phải

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số dưới (chỉ số thấp bên phải) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số trên (chỉ số cao bên phải) |

**Giá trị trả về:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Phần tử toán học mới loại [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Tạo chỉ số dưới và chỉ số trên ở phía bên phải

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| subscript | java.lang.String | Chỉ số dưới (chỉ số thấp bên phải) |
| superscript | java.lang.String | Chỉ số trên (chỉ số cao bên phải) |

**Giá trị trả về:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Phần tử toán học mới loại [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Tạo chỉ số dưới và chỉ số trên ở phía bên trái

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số dưới (chỉ số thấp bên trái) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số trên (chỉ số cao bên trái) |

**Giá trị trả về:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Phần tử toán học mới loại [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Tạo chỉ số dưới và chỉ số trên ở phía bên trái

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| subscript | java.lang.String | Chỉ số dưới (chỉ số thấp bên trái) |
| superscript | java.lang.String | Chỉ số trên (chỉ số cao bên trái) |

**Giá trị trả về:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Phần tử toán học mới loại [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Xác định căn bậc toán học của độ bậc đã cho từ đối số được chỉ định.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Đối số của căn bậc |

**Giá trị trả về:**
[IMathRadical](../../com.aspose.slides/imathradical) - Đối tượng mới loại [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Xác định căn bậc toán học của độ bậc đã cho từ đối số được chỉ định.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| degree | java.lang.String | Đối số của căn bậc |

**Giá trị trả về:**
[IMathRadical](../../com.aspose.slides/imathradical) - Đối tượng mới loại [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Lấy giới hạn trên

--------------------

> ```
public final IMathLimit setUpperLimit(IMathElement limit)
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn |

**Giá trị trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Đối tượng mới loại [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Lấy giới hạn trên

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| limit | java.lang.String | Giới hạn |

**Giá trị trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Đối tượng mới loại [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Lấy giới hạn dưới

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn |

**Giá trị trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Đối tượng mới loại [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Lấy giới hạn dưới

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| limit | java.lang.String | Giới hạn |

**Giá trị trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Đối tượng mới loại [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Tạo một toán tử N-ary

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kiểu toán tử N-ary |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn dưới |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn trên |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới loại [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Tạo một toán tử N-ary

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kiểu toán tử N-ary |
| lowerLimit | java.lang.String | Giới hạn dưới |
| upperLimit | java.lang.String | Giới hạn trên |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới loại [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Đặt vào một mảng dọc

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Giá trị trả về:**
[IMathArray](../../com.aspose.slides/imatharray) - Đối tượng mới loại [IMathArray](../../com.aspose.slides/imatharray)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Lấy tích phân

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | int | Kiểu tích phân |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn dưới của tích phân |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn trên của tích phân |
| limitLocations | int | Vị trí của giới hạn |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới loại [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Lấy tích phân

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | int | Kiểu tích phân |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn dưới của tích phân |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Giới hạn trên của tích phân |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới loại [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Lấy tích phân không có giới hạn

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | int | Kiểu tích phân |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới loại [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Lấy tích phân

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | int | Kiểu tích phân |
| lowerLimit | java.lang.String | Giới hạn dưới của tích phân |
| upperLimit | java.lang.String | Giới hạn trên của tích phân |
| limitLocations | int | Vị trí của giới hạn |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới loại [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Lấy tích phân

--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | int | Kiểu tích phân |
| lowerLimit | java.lang.String | Giới hạn dưới của tích phân |
| upperLimit | java.lang.String | Giới hạn trên của tích phân |

**Giá trị trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới loại [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Đặt dấu nhấn (một ký tự ở trên phần tử này)

--------------------

> ```markdown
> Ví dụ:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| accentCharacter | char | Ký tự dấu nhấn. Giá trị phải nằm trong khoảng (U+0300-U+036F) hoặc (U+20D0-U+20EF) |

**Giá trị trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Đối tượng mới loại [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Đặt một thanh ở trên phần tử này

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Giá trị trả về:**
[IMathBar](../../com.aspose.slides/imathbar) - Đối tượng mới loại [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Đặt một thanh ở dưới phần tử này

--------------------

> ```
> Ví dụ:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Giá trị trả về:**
[IMathBar](../../com.aspose.slides/imathbar) - Đối tượng mới loại [IMathBar](../../com.aspose.slides/imathbar)

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới

--------------------

> ```
> Ví dụ:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Giá trị trả về:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Đối tượng mới loại [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác

--------------------

> ```
> Ví dụ:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| character | char | Ký tự nhóm như DẤU NGỌC NHỌN DƯỚI (U+23DF) hoặc bất kỳ ký tự nào khác |
| position | int | Vị trí của ký tự nhóm |
| verticalJustification | int | Căn dọc của ký tự nhóm. Xác định cách căn chỉnh đối tượng so với đường cơ sở. Ví dụ, khi ký tự nhóm ở trên đối tượng, VerticalJustification của Top cho biết phần trên của đối tượng nằm trên đường cơ sở; khi đặt thành Bottom, phần dưới của đối tượng nằm trên đường cơ sở |

**Giá trị trả về:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Đối tượng mới loại [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Đặt phần tử này vào một hộp viền

--------------------

> ```
> Ví dụ:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Giá trị trả về:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Hộp viền chứa phần tử này

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Đặt phần tử này vào một hộp viền

--------------------

> ```
> Ví dụ:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hideTop | boolean | Ẩn cạnh trên |
| hideBottom | boolean | Ẩn cạnh dưới |
| hideLeft | boolean | Ẩn cạnh trái |
| hideRight | boolean | Ẩn cạnh phải |
| strikethroughHorizontal | boolean | Gạch ngang ngang của hộp viền |
| strikethroughVertical | boolean | Gạch ngang dọc của hộp viền |
| strikethroughBottomLeftToTopRight | boolean | Gạch chéo từ dưới-trái lên trên-phải |
| strikethroughTopLeftToBottomRight | boolean | Gạch chéo từ trên-trái xuống dưới-phải |

**Giá trị trả về:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Hộp viền chứa phần tử này

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Đặt phần tử này vào một hộp phi thị (nhóm logic) được dùng để gom các thành phần của một phương trình hoặc các đoạn văn toán học khác. Một đối tượng được đóng khung có thể (ví dụ) đóng vai trò là bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, đóng vai trò là điểm ngắt dòng, hoặc được nhóm để không cho phép ngắt dòng bên trong.

--------------------

> ```
> Ví dụ:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Giá trị trả về:**
[IMathBox](../../com.aspose.slides/imathbox) - Hộp logic chứa phần tử này

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Lấy các phần tử con

**Giá trị trả về:**
com.aspose.slides.IMathElement[] - Mảng của [IMathElement](../../com.aspose.slides/imathelement)