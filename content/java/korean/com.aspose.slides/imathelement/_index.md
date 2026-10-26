---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: 다양한 요소를 가진 수학 요소(분수, 수학 텍스트, 함수, 표현식 등)의 기본 인터페이스
type: docs
url: /ko/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

다양한 요소를 가진 수학 요소(분수, 수학 텍스트, 함수, 표현식 등)의 기본 인터페이스

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 수학 요소를 결합하여 수학 블록을 생성합니다 |
| [join(String mathText)](#join-java.lang.String-) | 수학 텍스트를 결합하여 수학 블록을 생성합니다 |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [divide(String denominator)](#divide-java.lang.String-) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [enclose()](#enclose--) | 수학 요소를 괄호로 둘러씁니다 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 이 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레임화합니다 |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [function(String functionArgument)](#function-java.lang.String-) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다 |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다 |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 아래 첨자를 생성합니다 |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 아래 첨자를 생성합니다 |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 위 첨자를 생성합니다 |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 위 첨자를 생성합니다 |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 지정된 인수로부터 주어진 차수의 수학적 루트를 지정합니다. |
| [radical(String degree)](#radical-java.lang.String-) | 지정된 인수로부터 주어진 차수의 수학적 루트를 지정합니다. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 상한을 지정합니다 |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 상한을 지정합니다 |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 하한을 지정합니다 |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 하한을 지정합니다 |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N-항 연산자를 생성합니다 |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N-항 연산자를 생성합니다 |
| [toMathArray()](#toMathArray--) | 수직 배열을 삽입합니다 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 적분을 취합니다 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 적분을 취합니다 |
| [integral(int integralType)](#integral-int-) | 한계 없이 적분을 취합니다 |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 적분을 취합니다 |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 적분을 취합니다 |
| [accent(char accentCharacter)](#accent-char-) | 강세 기호를 설정합니다(이 요소 위의 문자) |
| [overbar()](#overbar--) | 이 요소 위에 바를 설정합니다 |
| [underbar()](#underbar--) | 이 요소 아래에 바를 설정합니다 |
| [group()](#group--) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 하단 중괄호 또는 다른 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [toBorderBox()](#toBorderBox--) | 이 요소를 경계 상자에 배치합니다 |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 이 요소를 경계 상자에 배치합니다 |
| [toBox()](#toBox--) | 수식 구성 요소 혹은 기타 수학 텍스트 인스턴스를 그룹화하기 위해 사용되는 비시각적 상자(논리적 그룹)에 이 요소를 배치합니다. |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

자식 요소를 가져옵니다

**반환:**
com.aspose.slides.IMathElement[]

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

수학 요소를 결합하여 수학 블록을 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 결합될 요소 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 이 인스턴스와 지정된 인수를 포함하는 새로운 IMathBlock

### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

수학 텍스트를 결합하여 수학 블록을 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 결합될 수학 텍스트 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 이 인스턴스와 지정된 인수를 포함하는 새로운 IMathBlock

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

이 분자와 지정된 분모로 분수를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새로운 분수

### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

이 분자와 지정된 분모로 분수를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | java.lang.String | 분모 |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새로운 분수

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |
| fractionType | int | 분수 유형: Bar, NoBar, Skewed, Linear |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새로운 분수

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | java.lang.String | 분모 |
| fractionType | int | 분수 유형: Bar, NoBar, Skewed, Linear |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새로운 분수

### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

수학 요소를 괄호로 둘러씁니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**반환:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 유형 [IMathDelimiter](../../com.aspose.slides/imathdelimiter)인 수학 요소(괄호 포함)

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

이 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레임화합니다

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| beginningCharacter | char | 시작 문자(보통 왼쪽 괄호) |
| endingCharacter | char | 끝 문자(보통 오른쪽 괄호) |

**반환:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 유형 [IMathDelimiter](../../com.aspose.slides/imathdelimiter)인 수학 요소(지정된 문자로 프레임화)

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다

--------------------

> ```
> 예시:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | 함수의 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 유형 [IMathFunction](../../com.aspose.slides/imathfunction)인 새로운 수학 요소

### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다

--------------------

> ```
> 예시:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functionArgument | java.lang.String | 함수의 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 유형 [IMathFunction](../../com.aspose.slides/imathfunction)인 새로운 수학 요소

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다

--------------------

> ```
> 예시:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 함수 이름 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 유형 [IMathFunction](../../com.aspose.slides/imathfunction)인 새로운 수학 요소

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다

--------------------

> ```
> 예시:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functionName | java.lang.String | 함수 이름 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 유형 [IMathFunction](../../com.aspose.slides/imathfunction)인 새로운 수학 요소

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다

--------------------

> ```
> 예시:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functionType | int | 하나의 인수를 갖는 일반 함수 유형 중 하나 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 유형 [IMathFunction](../../com.aspose.slides/imathfunction)인 새로운 수학 요소

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x'를 밑이 '5'인 로그를 반환합니다
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functionType | int | 두 개 인수를 갖는 일반 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 함수 유형에 따라 달라지는 추가 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 유형 [IMathFunction](../../com.aspose.slides/imathfunction)인 새로운 수학 요소

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다

--------------------

> ```
> 예시:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x'를 밑이 '5'인 로그를 반환합니다
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functionType | int | 두 개 인수를 갖는 일반 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | 함수 유형에 따라 달라지는 추가 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 유형 [IMathFunction](../../com.aspose.slides/imathfunction)인 새로운 수학 요소

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

아래 첨자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽 아래 인덱스(하첨자) |

**반환:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 유형 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)인 새로운 수학 요소

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

아래 첨자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| subscript | java.lang.String | 오른쪽 아래 인덱스(하첨자) |

**반환:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 유형 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)인 새로운 수학 요소

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

위 첨자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽 위 인덱스(상첨자) |

**반환:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 유형 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)인 새로운 수학 요소

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

위 첨자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| superscript | java.lang.String | 오른쪽 위 인덱스(상첨자) |

**반환:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 유형 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)인 새로운 수학 요소

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

오른쪽에 아래 첨자와 위 첨자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽 아래 인덱스(하첨자) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽 위 인덱스(상첨자) |

**반환:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 유형 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)인 새로운 수학 요소

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
오른쪽에 아래첨자와 위첨자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| subscript | java.lang.String | 아래첨자 (오른쪽의 하위 인덱스) |
| superscript | java.lang.String | 위첨자 (오른쪽의 상위 인덱스) |

**반환:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 새 수학 요소 유형 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

왼쪽에 아래첨자와 위첨자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 아래첨자 (왼쪽의 하위 인덱스) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 위첨자 (왼쪽의 상위 인덱스) |

**반환:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 새 수학 요소 유형 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

왼쪽에 아래첨자와 위첨자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| subscript | java.lang.String | 아래첨자 (왼쪽의 하위 인덱스) |
| superscript | java.lang.String | 위첨자 (왼쪽의 상위 인덱스) |

**반환:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 새 수학 요소 유형 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

주어진 차수와 지정된 인수로부터 수학적 루트를 지정합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | 근호의 인수 |

**반환:**
[IMathRadical](../../com.aspose.slides/imathradical) - 새 인스턴스 유형 [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

주어진 차수와 지정된 인수로부터 수학적 루트를 지정합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| degree | java.lang.String | 근호의 인수 |

**반환:**
[IMathRadical](../../com.aspose.slides/imathradical) - 새 인스턴스 유형 [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

상한을 지정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 제한 |

**반환:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 인스턴스 유형 [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

상한을 지정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| limit | java.lang.String | 제한 |

**반환:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 인스턴스 유형 [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

하한을 지정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 제한 |

**반환:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 인스턴스 유형 [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

하한을 지정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| limit | java.lang.String | 제한 |

**반환:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 인스턴스 유형 [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

N-항 연산자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | N-항 연산자 유형 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 하한 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 상한 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

N-항 연산자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | N-항 연산자 유형 |
| lowerLimit | java.lang.String | 하한 |
| upperLimit | java.lang.String | 상한 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

수직 배열에 넣습니다

--------------------

> ```
> 예시:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**반환:**
[IMathArray](../../com.aspose.slides/imatharray) - 새 인스턴스 유형 [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

적분을 지정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| integralType | int | 적분 유형 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 적분의 하한 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 적분의 상한 |
| limitLocations | int | 제한 위치 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

적분을 지정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| integralType | int | 적분 유형 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 적분의 하한 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 적분의 상한 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

제한 없이 적분을 지정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| integralType | int | 적분 유형 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

적분을 지정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| integralType | int | 적분 유형 |
| lowerLimit | java.lang.String | 적분의 하한 |
| upperLimit | java.lang.String | 적분의 상한 |
| limitLocations | int | 제한 위치 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

적분을 지정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| integralType | int | 적분 유형 |
| lowerLimit | java.lang.String | 적분의 하한 |
| upperLimit | java.lang.String | 적분의 상한 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

액센트 부호를 설정합니다 (이 요소 위에 표시되는 문자)

--------------------

> ```
> 예시:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| accentCharacter | char | 액센트 문자. 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다 |

**반환:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 새 인스턴스 유형 [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

이 요소 위에 바를 설정합니다

--------------------

> ```
> 예시:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**반환:**
[IMathBar](../../com.aspose.slides/imathbar) - 새 인스턴스 유형 [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

이 요소 아래에 바를 설정합니다

--------------------

> ```
> 예시:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```


**반환:**
[IMathBar](../../com.aspose.slides/imathbar) - 새 인스턴스 유형 [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

이 요소를 하단 중괄호를 사용하여 그룹에 배치합니다

--------------------

> ```
> 예시:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```


**반환:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새 인스턴스 유형 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

이 요소를 하단 중괄호 등과 같은 그룹화 문자를 사용하여 그룹에 배치합니다

--------------------

> ```
> 예시:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| character | char | 그룹화 문자, 예: 하단 중괄호 (U+23DF) 또는 기타 |
| position | int | 그룹화 문자의 위치 |
| verticalJustification | int | 그룹 문자에 대한 수직 정렬. 객체가 기준선과 어떻게 정렬되는지를 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, VerticalJustification이 Top이면 객체 상단이 기준선에 맞춰지고, Bottom이면 객체 하단이 기준선에 맞춰집니다 |

**반환:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새 인스턴스 유형 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

이 요소를 테두리 박스에 배치합니다

--------------------

> ```
> 예시:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```


**반환:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 이 요소가 포함된 테두리 박스
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

이 요소를 테두리 박스에 배치합니다

--------------------

> ```
> 예시:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hideTop | boolean | 상단 가장자리 숨기기 |
| hideBottom | boolean | 하단 가장자리 숨기기 |
| hideLeft | boolean | 좌측 가장자리 숨기기 |
| hideRight | boolean | 우측 가장자리 숨기기 |
| strikethroughHorizontal | boolean | 테두리 박스 가로 획 그리기 |
| strikethroughVertical | boolean | 테두리 박스 세로 획 그리기 |
| strikethroughBottomLeftToTopRight | boolean | 테두리 박스 왼쪽 하단에서 오른쪽 상단까지 획 그리기 |
| strikethroughTopLeftToBottomRight | boolean | 테두리 박스 왼쪽 상단에서 오른쪽 하단까지 획 그리기 |

**반환:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 이 요소가 포함된 테두리 박스
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

이 요소를 비시각 박스(논리적 그룹) 안에 배치합니다. 이 박스는 식이나 다른 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. 박스 안의 객체는 정렬점이 있든 없든 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점이 되거나, 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다.

--------------------

> ```
> 예시:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**반환:**
[IMathBox](../../com.aspose.slides/imathbox) - 이 요소가 포함된 논리 박스