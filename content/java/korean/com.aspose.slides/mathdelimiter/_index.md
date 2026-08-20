---
title: MathDelimiter
second_title: Java용 Aspose.Slides API 참조
description: 괄호, 중괄호, 대괄호 및 수직 막대와 같은 여는 문자와 닫는 문자로 구성된 구분자 객체를 지정하며, 지정된 문자로 구분된 하나 이상의 수학 요소를 내부에 포함합니다.
type: docs
url: /ko/com.aspose.slides/mathdelimiter/
---
**상속:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

구분자 객체를 지정합니다. 이 객체는 여는 문자와 닫는 문자(예: 괄호, 중괄호, 대괄호 및 수직 막대)로 구성되며, 지정된 문자를 사용해 구분된 하나 이상의 수학 요소를 포함합니다. 예시: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | 지정된 요소를 단일 기본 인수로 사용하여 MathDelimiter를 초기화합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getArguments()](#getArguments--) | 구분자 문자로 구분된 하나 이상의 수학 요소 |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character는 시작, 즉 여는 구분자 문자를 지정합니다. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character는 시작, 즉 여는 구분자 문자를 지정합니다. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character는 구분자 객체에서 인수를 구분하는 문자를 지정합니다. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character는 구분자 객체에서 인수를 구분하는 문자를 지정합니다. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character는 종료, 즉 닫는 구분자 문자를 지정합니다. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character는 종료, 즉 닫는 구분자 문자를 지정합니다. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. true인 경우, 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. true인 경우, 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. |
| [getDelimiterShape()](#getDelimiterShape--) | 구분자 객체에서 구분자의 모양을 지정합니다. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | 구분자 객체에서 구분자의 모양을 지정합니다. |
| [delimit(char separatorCharacter)](#delimit-char-) | 지정된 구분자 문자를 사용하여 인수를 구분합니다. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레임을 만듭니다. |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |

### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

지정된 요소를 단일 기본 인수로 사용하여 MathDelimiter를 초기화합니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 구분자가 적용되는 기본 요소입니다. null일 수 있습니다. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

구분자 문자로 구분된 하나 이상의 수학 요소

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**반환값:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character는 시작, 즉 여는 구분자 문자를 지정합니다. 수학 구분자는 괄호, 대괄호 및 중괄호와 같은 둘러싸는 문자입니다. 기본값: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**반환값:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character는 시작, 즉 여는 구분자 문자를 지정합니다. 수학 구분자는 괄호, 대괄호 및 중괄호와 같은 둘러싸는 문자입니다. 기본값: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character는 구분자 객체에서 인수를 구분하는 문자를 지정합니다. 기본값: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**반환값:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character는 구분자 객체에서 인수를 구분하는 문자를 지정합니다. 기본값: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Delimiter Ending Character는 종료, 즉 닫는 구분자 문자를 지정합니다. 수학 구분자는 괄호, 대괄호 및 중괄호와 같은 둘러싸는 문자입니다. 기본값: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**반환값:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character는 종료, 즉 닫는 구분자 문자를 지정합니다. 수학 구분자는 괄호, 대괄호 및 중괄호와 같은 둘러싸는 문자입니다. 기본값: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. true인 경우, 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. 기본값은 true입니다.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**반환값:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. true인 경우, 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. 기본값은 true입니다.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

구분자 객체에서 구분자의 모양을 지정합니다. MathDelimiterShape.Centered인 경우, 구분자는 수학 텍스트의 수학 축을 중심으로 배치되고 내용 전체 높이에 맞게 조정될 수 있습니다. MathDelimiterShape.Match인 경우, 높이와 모양이 내용에 정확히 맞게 변경됩니다.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**반환값:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

구분자 객체에서 구분자의 모양을 지정합니다. MathDelimiterShape.Centered인 경우, 구분자는 수학 텍스트의 수학 축을 중심으로 배치되고 내용 전체 높이에 맞게 조정될 수 있습니다. MathDelimiterShape.Match인 경우, 높이와 모양이 내용에 정확히 맞게 변경됩니다.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

지정된 구분자 문자를 사용하여 인수를 구분합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| separatorCharacter | char | 구분자 문자 |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 구분자 문자를 적용한 후의 이 객체
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레임을 만듭니다

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| beginningCharacter | char | 시작 문자(보통 왼쪽 괄호) |
| endingCharacter | char | 끝 문자(보통 오른쪽 괄호) |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - beginningCharacter와 endingCharacter가 null인 경우, 해당 속성들에 값만 할당되고 새로운 객체가 생성되지 않습니다(이 인스턴스를 반환). 그렇지 않으면, 지정된 문자를 프레임으로 포함하고 이 [MathDelimiter](../../com.aspose.slides/mathdelimiter) 인스턴스를 내부에 프레임한 Delimiter 유형의 새로운 수학 요소를 반환합니다.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

자식 요소를 가져옵니다

**반환값:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps