---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: Giao diện cơ bản của bất kỳ phần tử toán học nào: phân số, văn bản toán học, hàm, biểu thức với nhiều phần tử, v.v.
type: docs
url: /vi/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Giao diện cơ bản của bất kỳ phần tử toán học nào: phân số, văn bản toán học, hàm, biểu thức với nhiều phần tử, v.v.

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Phương thức

| Method | Description |
| --- | --- |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Nối một phần tử toán học và tạo một khối toán học |
| [join(String mathText)](#join-java.lang.String-) | Nối một văn bản toán học và tạo một khối toán học |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [divide(String denominator)](#divide-java.lang.String-) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số được chỉ định |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số được chỉ định |
| [enclose()](#enclose--) | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bao quanh phần tử này bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Lấy một hàm của một đối số, sử dụng đối tượng này làm tên hàm |
| [function(String functionArgument)](#function-java.lang.String-) | Lấy một hàm của một đối số, sử dụng đối tượng này làm tên hàm |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Tạo chỉ số dưới |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Tạo chỉ số dưới |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Tạo chỉ số trên |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Tạo chỉ số trên |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Chỉ định căn bậc của cấp số đã cho từ đối số được chỉ định. |
| [radical(String degree)](#radical-java.lang.String-) | Chỉ định căn bậc của cấp số đã cho từ đối số được chỉ định. |
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
| [group()](#group--) | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn phía dưới |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn phía dưới hoặc ký tự khác |
| [toBorderBox()](#toBorderBox--) | Đặt phần tử này vào một hộp viền |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Đặt phần tử này vào một hộp viền |
| [toBox()](#toBox--) | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) được dùng để nhóm các thành phần của một phương trình hoặc các trường hợp khác của văn bản toán học. |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```


Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```


Nối một phần tử toán học và tạo một khối toán học

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cần nối |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - Một IMathBlock mới chứa đối tượng này và đối số được chỉ định
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```


Nối một văn bản toán học và tạo một khối toán học

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
| mathText | java.lang.String | Văn bản toán học cần nối |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - Một IMathBlock mới chứa đối tượng này và đối số được chỉ định
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
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

**Trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số mới
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
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

**Trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số mới
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
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

**Trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số mới
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```


Tạo một phân số loại đã chỉ định với tử số này và mẫu số được chỉ định

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| denominator | java.lang.String | Mẫu số |
| fractionType | int | Kiểu phân số: Bar, NoBar, Skewed, Linear |

**Trả về:**
[IMathFraction](../../com.aspose.slides/imathfraction) - phân số mới
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```


Bao quanh một phần tử toán học bằng dấu ngoặc đơn

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Phần tử toán học loại [IMathDelimiter](../../com.aspose.slides/imathdelimiter) bao gồm dấu ngoặc
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Bao quanh phần tử này bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung

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
| beginningCharacter | char | Ký tự đầu (thường là ngoặc trái) |
| endingCharacter | char | Ký tự cuối (thường là ngoặc phải) |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Phần tử toán học loại [IMathDelimiter](../../com.aspose.slides/imathdelimiter) bao gồm các ký tự được chỉ định làm khung
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```


Lấy một hàm của một đối số, sử dụng đối tượng này làm tên hàm

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

**Trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```


Lấy một hàm của một đối số, sử dụng đối tượng này làm tên hàm

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionArgument | java.lang.String | Đối số của hàm |

**Trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
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
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Tên hàm |

**Trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```


Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionName | java.lang.String | Tên hàm |

**Trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```


Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số

--------------------

> ```
> Ví dụ:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | int | Một trong các kiểu hàm thường có một đối số |

**Trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```


Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định

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
| functionType | int | Một trong các kiểu hàm thường có hai đối số: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Đối số bổ sung tùy thuộc vào kiểu hàm |

**Trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```


Lấy hàm đã chỉ định, sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định

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
| functionType | int | Một trong các kiểu hàm thường có hai đối số: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Đối số bổ sung tùy thuộc vào kiểu hàm |

**Trả về:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Phần tử toán học mới loại [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số dưới (chỉ số thấp ở bên phải) |

**Trả về:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Phần tử toán học mới loại [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
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
| subscript | java.lang.String | Chỉ số dưới (chỉ số thấp ở bên phải) |

**Trả về:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Phần tử toán học mới loại [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số trên (chỉ số cao ở bên phải) |

**Trả về:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Phần tử toán học mới loại [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
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
| superscript | java.lang.String | Chỉ số trên (chỉ số cao ở bên phải) |

**Trả về:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Phần tử toán học mới loại [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


Tạo chỉ số dưới và chỉ số trên ở bên phải

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số dưới (chỉ số thấp ở bên phải) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số trên (chỉ số cao ở bên phải) |

**Trả về:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Phần tử toán học mới loại [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Creates subscript and superscript on the right
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
| subscript | java.lang.String | Chỉ số dưới (chỉ số thấp hơn ở bên phải) |
| superscript | java.lang.String | Chỉ số trên (chỉ số cao hơn ở bên phải) |

**Trả về:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Phần tử toán học mới loại [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Creates subscript and superscript on the left
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số dưới (chỉ số thấp hơn ở bên trái) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Chỉ số trên (chỉ số cao hơn ở bên trái) |

**Trả về:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Phần tử toán học mới loại [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Creates subscript and superscript on the left
--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| subscript | java.lang.String | Chỉ số dưới (chỉ số thấp hơn ở bên trái) |
| superscript | java.lang.String | Chỉ số trên (chỉ số cao hơn ở bên trái) |

**Trả về:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Phần tử toán học mới loại [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Specifies the mathematical root of the given degree from the specified argument.
--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Đối số của căn bậc |

**Trả về:**
[IMathRadical](../../com.aspose.slides/imathradical) - Đối tượng mới kiểu [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Specifies the mathematical root of the given degree from the specified argument.
--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| degree | java.lang.String | Đối số của căn bậc |

**Trả về:**
[IMathRadical](../../com.aspose.slides/imathradical) - Đối tượng mới kiểu [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

Takes upper limit
--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | giới hạn |

**Trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Đối tượng mới kiểu [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Takes upper limit
--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| limit | java.lang.String | giới hạn |

**Trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Đối tượng mới kiểu [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Takes lower limit
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
| limit | [IMathElement](../../com.aspose.slides/imathelement) | giới hạn |

**Trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Đối tượng mới kiểu [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Takes lower limit
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
| limit | java.lang.String | giới hạn |

**Trả về:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Đối tượng mới kiểu [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Creates a N-ary operator
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

**Trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới kiểu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Creates a N-ary operator
--------------------

> ```
> Ví dụ:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kiểu toán tử N-ary |
| lowerLimit | java.lang.String | Giới hạn dưới |
| upperLimit | java.lang.String | Giới hạn trên |

**Trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới kiểu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Puts in a vertical array
--------------------

> ```
> Ví dụ:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Trả về:**
[IMathArray](../../com.aspose.slides/imatharray) - Đối tượng mới kiểu [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Takes the integral
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
| limitLocations | int | vị trí của các giới hạn |

**Trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới kiểu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Takes the integral
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

**Trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới kiểu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

Takes the integral without limits
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

**Trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới kiểu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Takes the integral
--------------------

> ```
> Ví dụ:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | int | Kiểu tích phân |
| lowerLimit | java.lang.String | Giới hạn dưới của tích phân |
| upperLimit | java.lang.String | Giới hạn trên của tích phân |
| limitLocations | int | vị trí của các giới hạn |

**Trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới kiểu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Takes the integral
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

**Trả về:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Đối tượng mới kiểu [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

Sets an accent mark (a character on the top of this element)
--------------------

> ```
> Ví dụ:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| accentCharacter | char | Ký tự dấu phụ. Giá trị phải nằm trong phạm vi (U+0300\\u2013U+036F) hoặc (U+20D0\\u2013U+20EF) |

**Trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Đối tượng mới kiểu [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Sets a bar on the top of this element
--------------------

> ```
> Ví dụ:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Trả về:**
[IMathBar](../../com.aspose.slides/imathbar) - Đối tượng mới kiểu [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Sets a bar on the bottom of this element
--------------------

> ```
> Ví dụ:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Trả về:**
[IMathBar](../../com.aspose.slides/imathbar) - Đối tượng mới kiểu [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Places this element in a group using a bottom curly bracket
--------------------

> ```
> Ví dụ:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Trả về:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Đối tượng mới kiểu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Places this element in a group using a grouping character such as bottom curly bracket or another
--------------------

> ```
> Ví dụ:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| character | char | Ký tự nhóm như BOTTOM CURLY BRACKET (U+23DF) hoặc bất kỳ ký tự nào khác |
| position | int | Vị trí của ký tự nhóm |
| verticalJustification | int | Canh dọc của ký tự nhóm. Xác định vị trí của đối tượng so với đường cơ sở. Ví dụ, khi ký tự nhóm ở trên đối tượng, VerticalJustification = Top có nghĩa là phần trên của đối tượng nằm trên đường cơ sở; khi VerticalJustification = Bottom, phần dưới của đối tượng nằm trên đường cơ sở |

**Trả về:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Đối tượng mới kiểu [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

Places this element in a border-box
--------------------

> ```
> Ví dụ:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Trả về:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box với phần tử này được đặt bên trong
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Places this element in a border-box
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
| strikethroughHorizontal | boolean | Gạch ngang ngang trong Border Box |
| strikethroughVertical | boolean | Gạch ngang dọc trong Border Box |
| strikethroughBottomLeftToTopRight | boolean | Gạch chéo từ dưới trái lên trên phải trong Border Box |
| strikethroughTopLeftToBottomRight | boolean | Gạch chéo từ trên trái xuống dưới phải trong Border Box |

**Trả về:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box với phần tử này được đặt bên trong
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.
--------------------

> ```
> Ví dụ:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Trả về:**
[IMathBox](../../com.aspose.slides/imathbox) - Logical box với phần tử này được đặt bên trong