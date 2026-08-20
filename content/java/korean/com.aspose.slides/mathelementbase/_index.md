---
title: MathElementBase
second_title: Java용 Aspose.Slides API 레퍼런스
description: 모든 파생 클래스에서 공통으로 사용되는 몇몇 메서드 구현을 포함하는 IMathElement의 기본 클래스입니다. 내부용으로만 사용됩니다.
type: docs
url: /ko/com.aspose.slides/mathelementbase/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

IMathElement에 대한 기본 클래스이며, 모든 상속 클래스에 공통적인 몇몇 메서드의 구현을 포함합니다. 내부 전용입니다. 상속 클래스는 IMathElement여야 합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate 객체를 반환합니다. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 수학 요소를 결합하여 수학 블록을 생성합니다. |
| [join(String mathText)](#join-java.lang.String-) | 수학 텍스트를 결합하여 수학 블록을 생성합니다. |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다. |
| [divide(String denominator)](#divide-java.lang.String-) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다. |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [enclose()](#enclose--) | 수학 요소를 괄호로 둘러씁니다. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 감싸서 프레임을 만듭니다. |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 받아들입니다. |
| [function(String functionArgument)](#function-java.lang.String-) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 받아들입니다. |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | 이 인스턴스를 인수로 사용하여 지정된 함수를 받아들입니다. |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | 이 인스턴스를 인수로 사용하여 지정된 함수를 받아들입니다. |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | 이 인스턴스를 인수로 사용하여 지정된 함수를 받아들입니다. |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 받아들입니다. |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 받아들입니다. |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 아래첨자를 생성합니다. |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 아래첨자를 생성합니다. |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 위첨자를 생성합니다. |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 위첨자를 생성합니다. |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 주어진 차수의 수학적 루트를 지정된 인수에서 지정합니다. |
| [radical(String degree)](#radical-java.lang.String-) | 주어진 차수의 수학적 루트를 지정된 인수에서 지정합니다. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 상한을 지정합니다. |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 상한을 지정합니다. |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 하한을 지정합니다. |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 하한을 지정합니다. |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N-항 연산자를 생성합니다. |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N-항 연산자를 생성합니다. |
| [toMathArray()](#toMathArray--) | 수직 배열을 삽입합니다. |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 적분을 수행합니다. |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 적분을 수행합니다. |
| [integral(int integralType)](#integral-int-) | 한계 없이 적분을 수행합니다. |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 적분을 수행합니다. |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 적분을 수행합니다. |
| [accent(char accentCharacter)](#accent-char-) | 이 요소 위에 억양 부호(문자)를 설정합니다. |
| [overbar()](#overbar--) | 이 요소 위에 바를 설정합니다. |
| [underbar()](#underbar--) | 이 요소 아래에 바를 설정합니다. |
| [group()](#group--) | 아래 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 아래 중괄호 등 그룹화 문자로 이 요소를 그룹에 배치합니다. |
| [toBorderBox()](#toBorderBox--) | 이 요소를 테두리 상자에 배치합니다. |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 이 요소를 테두리 상자에 배치합니다. |
| [toBox()](#toBox--) | 이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다. 이는 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다. |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

수학 요소를 결합하여 수학 블록을 생성합니다.

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 결합할 요소 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 이 인스턴스와 지정된 인수가 포함된 새로운 IMathBlock

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

수학 텍스트를 결합하여 수학 블록을 생성합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 결합할 수학 텍스트 |

**반환:**
[IMathBlock](../../com.aspose.slides/imathblock) - 이 인스턴스와 지정된 인수가 포함된 새로운 IMathBlock

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

이 분자와 지정된 분모를 사용하여 분수를 생성합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 분수

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

이 분자와 지정된 분모를 사용하여 분수를 생성합니다.

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| denominator | java.lang.String | 분모 |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 분수

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |
| fractionType | int | 분수 유형: Bar, NoBar, Skewed, Linear |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 분수

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| denominator | java.lang.String | 분모 |
| fractionType | int | 분수 유형: Bar, NoBar, Skewed, Linear |

**반환:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 분수

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

수학 요소를 괄호로 둘러씁니다.

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**반환:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 유형의 수학 요소(괄호 포함)

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 감싸서 프레임을 만듭니다.

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| beginningCharacter | char | 시작 문자(보통 왼쪽 괄호) |
| endingCharacter | char | 종료 문자(보통 오른쪽 괄호) |

**반환:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 유형의 수학 요소(지정된 문자로 프레임)

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 받아들입니다.

--------------------

> ```
> 예시:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | 함수의 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 새로운 수학 요소

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 받아들입니다.

--------------------

> ```
> 예시:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionArgument | java.lang.String | 함수의 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 새로운 수학 요소

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

이 인스턴스를 인수로 사용하여 지정된 함수를 받아들입니다.

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 함수 이름 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 새로운 수학 요소

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

이 인스턴스를 인수로 사용하여 지정된 함수를 받아들입니다.

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionName | java.lang.String | 함수 이름 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 새로운 수학 요소

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

이 인스턴스를 인수로 사용하여 지정된 함수를 받아들입니다.

--------------------

> ```
> 예시:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionType | int | 하나의 인수를 받는 일반 함수 유형 중 하나 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 새로운 수학 요소

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 받아들입니다.

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x'의 로그를 밑 '5'로 반환합니다
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionType | int | 두 인수를 받는 일반 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 함수 유형에 따라 달라지는 추가 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 새로운 수학 요소

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 받아들입니다.

--------------------

> ```
> 예시:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x'의 로그를 밑 '5'로 반환합니다
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionType | int | 두 인수를 받는 일반 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | 함수 유형에 따라 달라지는 추가 인수 |

**반환:**
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 유형의 새로운 수학 요소

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

아래첨자를 생성합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽에 아래첨자(하위 인덱스) |

**반환:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 유형의 새로운 수학 요소

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

아래첨자를 생성합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| subscript | java.lang.String | 오른쪽에 아래첨자(하위 인덱스) |

**반환:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 유형의 새로운 수학 요소

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

위첨자를 생성합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽에 위첨자(상위 인덱스) |

**반환:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 유형의 새로운 수학 요소

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

위첨자를 생성합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| superscript | java.lang.String | 오른쪽에 위첨자(상위 인덱스) |

**반환:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 유형의 새로운 수학 요소

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

오른쪽에 아래첨자와 위첨자를 생성합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽에 아래첨자(하위 인덱스) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 오른쪽에 위첨자(상위 인덱스) |

**반환:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 유형의 새로운 수학 요소

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

오른쪽에 아래첨자와 위첨자를 생성합니다.
> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |
| superscript | java.lang.String | Superscript (upper index on the right) |

**반환값:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 새 수학 요소 유형 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
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
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the left) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the left) |

**반환값:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 새 수학 요소 유형 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

왼쪽에 아래첨자와 위첨자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the left) |
| superscript | java.lang.String | Superscript (upper index on the left) |

**반환값:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 새 수학 요소 유형 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

주어진 차수의 수학적 루트를 지정된 인수에서 구합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument of Radical |

**반환값:**
[IMathRadical](../../com.aspose.slides/imathradical) - 새 인스턴스 유형 [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

주어진 차수의 수학적 루트를 지정된 인수에서 구합니다.

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument of Radical |

**반환값:**
[IMathRadical](../../com.aspose.slides/imathradical) - 새 인스턴스 유형 [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

상한을 설정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**반환값:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 인스턴스 유형 [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

상한을 설정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**반환값:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 인스턴스 유형 [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

하한을 설정합니다

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
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**반환값:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 인스턴스 유형 [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

하한을 설정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**반환값:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 인스턴스 유형 [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

N-ary 연산자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | The lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | The upper limit |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

N-ary 연산자를 생성합니다

--------------------

> ```
> 예시:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | java.lang.String | The lower limit |
| upperLimit | java.lang.String | The upper limit |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

수직 배열에 배치합니다

--------------------

> ```
> 예시:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**반환값:**
[IMathArray](../../com.aspose.slides/imatharray) - 새 인스턴스 유형 [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

적분을 설정합니다

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
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

적분을 설정합니다

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
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

한계 없이 적분을 설정합니다

--------------------

> ```
> 예시:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

적분을 설정합니다

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
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |
| limitLocations | int | location of limits |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

적분을 설정합니다

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
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 인스턴스 유형 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

이 요소 위에 악센트 표시(문자)를 설정합니다

--------------------

> ```
> 예시:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

**반환값:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 새 인스턴스 유형 [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

이 요소 위에 가로선을 설정합니다

--------------------

> ```
> 예시:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**반환값:**
[IMathBar](../../com.aspose.slides/imathbar) - 새 인스턴스 유형 [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

이 요소 아래에 가로선을 설정합니다

--------------------

> ```
> 예시:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```


**반환값:**
[IMathBar](../../com.aspose.slides/imathbar) - 새 인스턴스 유형 [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다

--------------------

> ```
> 예시:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**반환값:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새 인스턴스 유형 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

하단 중괄호 등 그룹 문자로 이 요소를 그룹에 배치합니다

--------------------

> ```
> 예시:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | int | Position of grouping character |
| verticalJustification | int | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

**반환값:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새 인스턴스 유형 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

이 요소를 테두리 상자에 배치합니다

--------------------

> ```
> 예시:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**반환값:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 이 요소가 포함된 테두리 상자
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

이 요소를 테두리 상자에 배치합니다

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**반환값:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 이 요소가 포함된 테두리 상자
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

이 요소를 비시각적 박스(논리적 그룹) 안에 배치합니다. 이 박스는 수식의 구성 요소나 다른 수학 텍스트 인스턴스를 그룹화하는 데 사용됩니다. 박스 안의 객체는 정렬점이 있거나 없거나에 따라 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점으로 사용되거나, 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다.

--------------------

> ```
> 예시:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**반환값:**
[IMathBox](../../com.aspose.slides/imathbox) - 이 요소가 포함된 논리 박스
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

자식 요소를 가져옵니다

**반환값:**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) 배열