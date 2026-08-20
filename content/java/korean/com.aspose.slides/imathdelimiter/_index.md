---
title: IMathDelimiter
second_title: Aspose.Slides for Java API 레퍼런스
description: 괄호, 중괄호, 대괄호 및 수직 막대와 같은 여는 문자와 닫는 문자로 구성된 구분자 객체를 지정하며, 지정된 문자로 구분된 하나 이상의 수학 요소를 포함합니다.
type: docs
url: /ko/com.aspose.slides/imathdelimiter/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

구분자 객체를 지정합니다. 이 객체는 여는 문자와 닫는 문자(예: 괄호, 중괄호, 대괄호 및 수직 막대)로 구성되며, 지정된 문자로 구분된 하나 이상의 수학 요소를 포함합니다. 예시: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
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
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장 여부를 지정합니다. true인 경우, 구분자는 피연산자 높이에 맞게 수직으로 늘어납니다. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장 여부를 지정합니다. true인 경우, 구분자는 피연산자 높이에 맞게 수직으로 늘어납니다. |
| [getDelimiterShape()](#getDelimiterShape--) | 구분자 객체에서 구분자의 모양을 지정합니다. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | 구분자 객체에서 구분자의 모양을 지정합니다. |
| [delimit(char separatorCharacter)](#delimit-char-) | 지정된 구분자 문자를 사용하여 인수를 구분합니다. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
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
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character는 시작, 즉 여는 구분자 문자를 지정합니다. 수학 구분자는 괄호, 대괄호 및 중괄호와 같은 둘러싸는 문자입니다. 기본값: '('.

--------------------

> ```
> Example:
>  
>  IMMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**반환값:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
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
public abstract void setSeparatorCharacter(char value)
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
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
public abstract void setEndingCharacter(char value)
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장 여부를 지정합니다. true인 경우, 구분자는 피연산자 높이에 맞게 수직으로 늘어납니다. 기본값은 true입니다.

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
public abstract void setGrowToMatchOperandHeight(boolean value)
```

BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장 여부를 지정합니다. true인 경우, 구분자는 피연산자 높이에 맞게 수직으로 늘어납니다. 기본값은 true입니다.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

구분자 객체에서 구분자의 모양을 지정합니다. MathDelimiterShape.Centered인 경우, 구분자는 수학 텍스트의 수학 축을 중심으로 배치되며 내용 전체 높이에 맞게 조정됩니다. MathDelimiterShape.Match인 경우, 구분자의 높이와 모양이 내용에 정확히 맞도록 변경됩니다.

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
public abstract void setDelimiterShape(int value)
```

구분자 객체에서 구분자의 모양을 지정합니다. MathDelimiterShape.Centered인 경우, 구분자는 수학 텍스트의 수학 축을 중심으로 배치되며 내용 전체 높이에 맞게 조정됩니다. MathDelimiterShape.Match인 경우, 구분자의 높이와 모양이 내용에 정확히 맞도록 변경됩니다.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

지정된 구분자 문자를 사용하여 인수를 구분합니다.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separatorCharacter | char | delimiter character |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 이 객체는 구분자 문자를 적용한 후의 결과입니다