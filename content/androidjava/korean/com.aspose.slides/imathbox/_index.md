---
title: IMathBox
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 수학 요소의 논리적 박싱(패키징)을 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathbox/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

수학 요소의 논리적 박싱(패키징)을 지정합니다. 예를 들어, 박스된 객체는 정렬 지점이 있거나 없을 때 연산자 에뮬레이터로 사용할 수 있으며, 줄 바꿈 지점으로 작동하거나, 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. 예를 들어, "==" 연산자는 줄 바꿈을 방지하도록 박스되어야 합니다.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getOperatorEmulator()](#getOperatorEmulator--) | 연산자 에뮬레이터. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | 연산자 에뮬레이터. |
| [getNoBreak()](#getNoBreak--) | 줄 바꿈 없음. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | 줄 바꿈 없음. |
| [getDifferential()](#getDifferential--) | 미분. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | 미분. |
| [getAlignmentPoint()](#getAlignmentPoint--) | true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 방정식에 지정된 정렬 지점이 이에 맞춰 정렬될 수 있습니다. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 방정식에 지정된 정렬 지점이 이에 맞춰 정렬될 수 있습니다. |
| [getExplicitBreak()](#getExplicitBreak--) | 명시적 줄 바꿈은 Box 객체 시작 부분에 줄 바꿈이 있는지를 지정하며, 줄이 Box 객체 시작 부분에서 래핑됩니다. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | 명시적 줄 바꿈은 Box 객체 시작 부분에 줄 바꿈이 있는지를 지정하며, 줄이 Box 객체 시작 부분에서 래핑됩니다. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

기본 인수

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

연산자 에뮬레이터. true인 경우, 박스와 그 내용물은 단일 연산자로 동작하며 연산자의 속성을 상속합니다. 이는 예를 들어, 해당 문자가 줄 바꿈 지점으로 사용될 수 있고 다른 연산자와 정렬될 수 있음을 의미합니다. 연산자 에뮬레이터는 '=='와 같이 하나 이상의 글리프가 결합하여 연산자를 형성할 때 자주 사용됩니다. 기본값: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**반환값:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

연산자 에뮬레이터. true인 경우, 박스와 그 내용물은 단일 연산자로 동작하며 연산자의 속성을 상속합니다. 이는 예를 들어, 해당 문자가 줄 바꿈 지점으로 사용될 수 있고 다른 연산자와 정렬될 수 있음을 의미합니다. 연산자 에뮬레이터는 '=='와 같이 하나 이상의 글리프가 결합하여 연산자를 형성할 때 자주 사용됩니다. 기본값: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

줄 바꿈 없음. 이 속성은 객체 박스의 "unbreakable" 속성을 지정합니다. true인 경우, 박스 내부에서 줄 바꿈이 발생하지 않습니다. 이는 둘 이상의 이항 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다. 이 요소가 지정되지 않으면, 박스 내부에서 줄 바꿈이 발생할 수 있습니다. 기본값: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**반환값:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

줄 바꿈 없음. 이 속성은 객체 박스의 "unbreakable" 속성을 지정합니다. true인 경우, 박스 내부에서 줄 바꿈이 발생하지 않습니다. 이는 둘 이상의 이항 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다. 이 요소가 지정되지 않으면, 박스 내부에서 줄 바꿈이 발생할 수 있습니다. 기본값: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

미분. true인 경우, 박스는 미분 역할을 하며(예: 적분식 안의 \ud835\udc51\ud835\udc65), 수학적 미분에 적절한 수평 간격을 받습니다. 기본값: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**반환값:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

미분. true인 경우, 박스는 미분 역할을 하며(예: 적분식 안의 \ud835\udc51\ud835\udc65), 수학적 미분에 적절한 수평 간격을 받습니다. 기본값: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 방정식에 지정된 정렬 지점이 이에 맞춰 정렬될 수 있습니다. 기본값: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**반환값:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 방정식에 지정된 정렬 지점이 이에 맞춰 정렬될 수 있습니다. 기본값: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

명시적 줄 바꿈은 Box 객체 시작 부분에 줄 바꿈이 있는지를 지정하며, 줄이 Box 객체 시작 부분에서 래핑됩니다. 이전 수학 텍스트 줄에 있는 연산자 번호를 현재 수학 텍스트 줄의 정렬 지점으로 사용할지 지정합니다. 가능한 값: 1..255 기본값: 0 (명시적 줄 바꿈 없음)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**반환값:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

명시적 줄 바꿈은 Box 객체 시작 부분에 줄 바꿈이 있는지를 지정하며, 줄이 Box 객체 시작 부분에서 래핑됩니다. 이전 수학 텍스트 줄에 있는 연산자 번호를 현재 수학 텍스트 줄의 정렬 지점으로 사용할지 지정합니다. 가능한 값: 1..255 기본값: 0 (명시적 줄 바꿈 없음)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |