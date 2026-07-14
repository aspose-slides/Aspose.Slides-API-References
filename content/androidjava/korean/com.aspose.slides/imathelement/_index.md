---
title: IMathElement
second_title: Aspose.Slides for Android via Java API Reference
description: 다중 요소 등을 포함한 수학 요소(분수, 수학 텍스트, 함수, 표현식)의 기본 인터페이스
type: docs
url: /ko/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

다중 요소 등을 포함한 수학 요소(분수, 수학 텍스트, 함수, 표현식)의 기본 인터페이스

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
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| [join(String mathText)](#join-java.lang.String-) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | 지정된 분모와 이 분자를 사용하여 분수를 생성합니다 |
| [divide(String denominator)](#divide-java.lang.String-) | 지정된 분모와 이 분자를 사용하여 분수를 생성합니다 |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [enclose()](#enclose--) | 수학 요소를 괄호로 감쌉니다 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 이 요소를 괄호 등 지정된 문자로 프레임화하여 감쌉니다 |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [function(String functionArgument)](#function-java.lang.String-) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다 |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다 |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 아래 첨자를 생성합니다 |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 아래 첨자를 생성합니다 |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 위 첨자를 생성합니다 |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 위 첨자를 생성합니다 |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [radical(String degree)](#radical-java.lang.String-) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 상한을 지정합니다 |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 상한을 지정합니다 |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 하한을 지정합니다 |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 하한을 지정합니다 |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N-ary 연산자를 생성합니다 |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N-ary 연산자를 생성합니다 |
| [toMathArray()](#toMathArray--) | 수직 배열에 넣습니다 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 적분을 취합니다 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 적분을 취합니다 |
| [integral(int integralType)](#integral-int-) | 제한 없이 적분을 취합니다 |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 적분을 취합니다 |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 적분을 취합니다 |
| [accent(char accentCharacter)](#accent-char-) | 이 요소 위에 악센트 기호(문자)를 설정합니다 |
| [overbar()](#overbar--) | 이 요소 위에 바를 설정합니다 |
| [underbar()](#underbar--) | 이 요소 아래에 바를 설정합니다 |
| [group()](#group--) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 하단 중괄호 등 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [toBorderBox()](#toBorderBox--) | 이 요소를 테두리 박스에 배치합니다 |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 이 요소를 테두리 박스에 배치합니다 |
| [toBox()](#toBox--) | 이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다. 이는 방정식 또는 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. |
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

수학 요소를 결합하여 수학 블록을 형성합니다

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 결합할 요소 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 지정된 인수를 포함하는 새 IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

수학 텍스트를 결합하여 수학 블록을 형성합니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | 결합할 수학 텍스트 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 지정된 인수를 포함하는 새 IMathBlock
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

지정된 분모와 이 분자를 사용하여 분수를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 분수
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

지정된 분모와 이 분자를 사용하여 분수를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | 분모 |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 분수
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
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |
| fractionType | int | 분수 유형: Bar, NoBar, Skewed, Linear |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 분수
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
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | 분모 |
| fractionType | int | 분수 유형: Bar, NoBar, Skewed, Linear |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 분수
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

수학 요소를 괄호로 감쌉니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**반환:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 괄호를 포함한 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 유형의 수학 요소
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

이 요소를 괄호 등 지정된 문자로 프레임화하여 감쌉니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | 시작 문자(보통 왼쪽 괄호) |
| endingCharacter | char | 종료 문자(보통 오른쪽 괄호) |

**반환:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 지정된 문자를 프레임으로 포함한 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 유형의 수학 요소
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | 함수의 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 새 [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 수학 요소
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | java.lang.String | 함수의 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 새 [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 수학 요소
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 함수 이름 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 새 [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 수학 요소
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionName | java.lang.String | 함수 이름 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 새 [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 수학 요소
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | 하나의 인수를 갖는 일반 함수 유형 중 하나 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 새 [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 수학 요소
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x'의 로그를 밑이 '5'인 경우 반환합니다
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | 두 인수를 갖는 일반 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 함수 유형에 따라 추가 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 새 [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 수학 요소
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x'의 로그를 밑이 '5'인 경우 반환합니다
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | 두 인수를 갖는 일반 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | 함수 유형에 따라 추가 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 새 [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 수학 요소
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

아래 첨자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽에 위치한 아래 첨자 |

**반환:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 새 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 유형의 수학 요소
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

아래 첨자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | 오른쪽에 위치한 아래 첨자 |

**반환:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 새 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 유형의 수학 요소
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

위 첨자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽에 위치한 위 첨자 |

**반환:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 새 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 유형의 수학 요소
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

위 첨자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| superscript | java.lang.String | 오른쪽에 위치한 위 첨자 |

**반환:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 새 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 유형의 수학 요소
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

오른쪽에 아래 첨자와 위 첨자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽에 위치한 아래 첨자 |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽에 위치한 위 첨자 |

**반환:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 새 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 유형의 수학 요소
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

오른쪽에 아래 첨자와 위 첨자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | 오른쪽에 위치한 아래 첨자 |
| superscript | java.lang.String | 오른쪽에 위치한 위 첨자 |

**반환:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 새 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 유형의 수학 요소
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

왼쪽에 아래 첨자와 위 첨자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 왼쪽에 위치한 아래 첨자 |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 왼쪽에 위치한 위 첨자 |

**반환:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 새 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) 유형의 수학 요소
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

왼쪽에 아래 첨자와 위 첨자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | 왼쪽에 위치한 아래 첨자 |
| superscript | java.lang.String | 왼쪽에 위치한 위 첨자 |

**반환:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 새 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) 유형의 수학 요소
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | 루트의 차수 |

**반환:**
[IMathRadical](../../com.aspose.slides/imathradical) - 새 [IMathRadical](../../com.aspose.slides/imathradical) 유형의 인스턴스
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | 루트의 차수 |

**반환:**
[IMathRadical](../../com.aspose.slides/imathradical) - 새 [IMathRadical](../../com.aspose.slides/imathradical) 유형의 인스턴스
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

상한을 지정합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 상한 |

**반환:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 [IMathLimit](../../com.aspose.slides/imathlimit) 유형의 인스턴스
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

상한을 지정합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | 상한 |

**반환:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 [IMathLimit](../../com.aspose.slides/imathlimit) 유형의 인스턴스
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

하한을 지정합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 하한 |

**반환:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 [IMathLimit](../../com.aspose.slides/imathlimit) 유형의 인스턴스
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

하한을 지정합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | 하한 |

**반환:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 [IMathLimit](../../com.aspose.slides/imathlimit) 유형의 인스턴스
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

N-ary 연산자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | N-ary 연산자 유형 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 하한 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 상한 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 유형의 인스턴스
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

N-ary 연산자를 생성합니다

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | N-ary 연산자 유형 |
| lowerLimit | java.lang.String | 하한 |
| upperLimit | java.lang.String | 상한 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 유형의 인스턴스
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

수직 배열에 넣습니다

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**반환:**
[IMathArray](../../com.aspose.slides/imatharray) - 새 [IMathArray](../../com.aspose.slides/imatharray) 유형의 인스턴스
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

적분을 취합니다

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
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | 적분 유형 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 적분의 하한 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 적분의 상한 |
| limitLocations | int | 제한 위치 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 유형의 인스턴스
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

적분을 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | 적분 유형 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 적분의 하한 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 적분의 상한 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 유형의 인스턴스
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

제한 없이 적분을 취합니다

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | 적분 유형 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 유형의 인스턴스
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

적분을 취합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | 적분 유형 |
| lowerLimit | java.lang.String | 적분의 하한 |
| upperLimit | java.lang.String | 적분의 상한 |
| limitLocations | int | 제한 위치 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 유형의 인스턴스
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

적분을 취합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | 적분 유형 |
| lowerLimit | java.lang.String | 적분의 하한 |
| upperLimit | java.lang.String | 적분의 상한 |

**반환:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 유형의 인스턴스
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

이 요소 위에 악센트 기호(문자)를 설정합니다

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | 악센트 문자. 값은 (U+0300-U+036F) 또는 (U+20D0-U+20EF) 범위에 있어야 합니다 |

**반환:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 새 [IMathAccent](../../com.aspose.slides/imathaccent) 유형의 인스턴스
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
[IMathBar](../../com.aspose.slides/imathbar) - 새 [IMathBar](../../com.aspose.slides/imathbar) 유형의 인스턴스
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
[IMathBar](../../com.aspose.slides/imathbar) - 새 [IMathBar](../../com.aspose.slides/imathbar) 유형의 인스턴스
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**반환:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 유형의 인스턴스
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

하단 중괄호 등 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | BOTTOM CURLY BRACKET (U+23DF) 등 그룹화 문자 |
| position | int | 그룹화 문자의 위치 |
| verticalJustification | int | 그룹 문자 수직 정렬. 기준선에 대한 객체 정렬을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있으면 Top은 객체 상단이 기준선에 맞춰짐을 의미하고, Bottom은 객체 하단이 기준선에 맞춰짐을 의미합니다. |

**반환:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 유형의 인스턴스
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

이 요소를 테두리 박스에 배치합니다

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**반환:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 내부에 이 요소가 배치된 테두리 박스
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

이 요소를 테두리 박스에 배치합니다

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | 상단 가장자리 숨기기 |
| hideBottom | boolean | 하단 가장자리 숨기기 |
| hideLeft | boolean | 왼쪽 가장자리 숨기기 |
| hideRight | boolean | 오른쪽 가장자리 숨기기 |
| strikethroughHorizontal | boolean | 가로선이 그어진 테두리 박스 |
| strikethroughVertical | boolean | 세로선이 그어진 테두리 박스 |
| strikethroughBottomLeftToTopRight | boolean | 왼쪽 아래에서 오른쪽 위로 그어진 테두리 박스 |
| strikethroughTopLeftToBottomRight | boolean | 왼쪽 위에서 오른쪽 아래로 그어진 테두리 박스 |

**반환:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 내부에 이 요소가 배치된 테두리 박스
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다. 이는 방정식 또는 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. 박스로 묶인 객체는 (예를 들어) 정렬점이 있거나 없거나에 따라 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점으로 사용되거나, 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**반환:**
[IMathBox](../../com.aspose.slides/imathbox) - 내부에 이 요소가 배치된 논리적 박스