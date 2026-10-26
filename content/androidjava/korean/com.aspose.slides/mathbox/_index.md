---
title: MathBox
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학 요소의 논리적 박싱 패키징을 지정합니다.
type: docs
url: /ko/com.aspose.slides/mathbox/
---
**상속:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**모든 구현된 인터페이스:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

수학 요소의 논리적 박싱(패키징)을 지정합니다. 예를 들어, 박싱된 객체는 정렬 지점이 있거나 없을 수 있는 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점으로 사용되거나, 박스 내부에서 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. 예를 들어, "==" 연산자는 줄 바꿈을 방지하기 위해 박싱되어야 합니다.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | 지정된 요소를 인수로 사용하여 MathBox를 초기화합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getOperatorEmulator()](#getOperatorEmulator--) | 연산자 에뮬레이터. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | 연산자 에뮬레이터. |
| [getNoBreak()](#getNoBreak--) | 줄 바꿈 방지: 이 속성은 객체 상자에 대한 "unbreakable" 속성을 지정합니다. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | 줄 바꿈 방지: 이 속성은 객체 상자에 대한 "unbreakable" 속성을 지정합니다. |
| [getDifferential()](#getDifferential--) | Differential true인 경우, 박스는 미분 연산자 역할을 하며(예: 적분식에서 \\ud835\\udc51\\ud835\\udc65), 수학적 미분에 적절한 수평 간격을 받습니다. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential true인 경우, 박스는 미분 연산자 역할을 하며(예: 적분식에서 \\ud835\\udc51\\ud835\\udc65), 수학적 미분에 적절한 수평 간격을 받습니다. |
| [getAlignmentPoint()](#getAlignmentPoint--) | true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작용합니다; 즉, 다른 방정식에서 지정된 정렬 지점과 정렬될 수 있습니다. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작용합니다; 즉, 다른 방정식에서 지정된 정렬 지점과 정렬될 수 있습니다. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break는 Box 객체 시작 부분에 줄 바꿈이 있는지를 지정합니다. 즉, 줄이 Box 객체 시작 부분에서 감싸집니다. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break는 Box 객체 시작 부분에 줄 바꿈이 있는지를 지정합니다. 즉, 줄이 Box 객체 시작 부분에서 감싸집니다. |
| [getChildren()](#getChildren--) | 자식 요소 가져오기 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


지정된 요소를 인수로 사용하여 MathBox를 초기화합니다

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 박스가 적용되는 기본 요소입니다. null일 수 있습니다. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


기본 인수

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Operator Emulator. true인 경우, 박스와 그 내용은 단일 연산자로 동작하며 연산자의 속성을 상속합니다. 이는 예를 들어, 문자가 줄 바꿈 지점으로 사용될 수 있고 다른 연산자와 정렬될 수 있음을 의미합니다. Operator Emulator는 '=='와 같이 하나 이상의 글리프가 결합하여 연산자를 형성할 때 자주 사용됩니다. 기본값: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**반환값:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Operator Emulator. true인 경우, 박스와 그 내용은 단일 연산자로 동작하며 연산자의 속성을 상속합니다. 이는 예를 들어, 문자가 줄 바꿈 지점으로 사용될 수 있고 다른 연산자와 정렬될 수 있음을 의미합니다. Operator Emulator는 '=='와 같이 하나 이상의 글리프가 결합하여 연산자를 형성할 때 자주 사용됩니다. 기본값: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


No break 이 속성은 객체 상자에 대한 "unbreakable" 속성을 지정합니다. true인 경우, 박스 내부에서 줄 바꿈이 발생하지 않습니다. 이는 둘 이상의 이항 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다. 이 요소가 지정되지 않으면 박스 내부에서 줄 바꿈이 발생할 수 있습니다. 기본값: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**반환값:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


No break 이 속성은 객체 상자에 대한 "unbreakable" 속성을 지정합니다. true인 경우, 박스 내부에서 줄 바꿈이 발생하지 않습니다. 이는 둘 이상의 이항 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다. 이 요소가 지정되지 않으면 박스 내부에서 줄 바꿈이 발생할 수 있습니다. 기본값: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Differential true인 경우, 박스는 미분 연산자 역할을 하며(예: 적분식에서 \\ud835\\udc51\\ud835\\udc65), 수학적 미분에 적절한 수평 간격을 받습니다. 기본값: false

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
public final void setDifferential(boolean value)
```


Differential true인 경우, 박스는 미분 연산자 역할을 하며(예: 적분식에서 \\ud835\\udc51\\ud835\\udc65), 수학적 미분에 적절한 수평 간격을 받습니다. 기본값: false

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```


true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작용합니다; 즉, 다른 방정식에서 지정된 정렬 지점과 정렬될 수 있습니다. 기본값: false

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
public final void setAlignmentPoint(boolean value)
```


true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작용합니다; 즉, 다른 방정식에서 지정된 정렬 지점과 정렬될 수 있습니다. 기본값: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```


Explicit break는 Box 객체 시작 부분에 줄 바꿈이 있는지를 지정합니다. 즉, 줄이 Box 객체 시작 부분에서 감싸집니다. 이전 수학 텍스트 줄의 연산자 번호를 지정하여 현재 수학 텍스트 줄의 정렬 지점으로 사용할 수 있습니다. 가능한 값: 1..255 기본값: 0 (명시적 줄 바꿈 없음)

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
public final void setExplicitBreak(byte value)
```


Explicit break는 Box 객체 시작 부분에 줄 바꿈이 있는지를 지정합니다. 즉, 줄이 Box 객체 시작 부분에서 감싸집니다. 이전 수학 텍스트 줄의 연산자 번호를 지정하여 현재 수학 텍스트 줄의 정렬 지점으로 사용할 수 있습니다. 가능한 값: 1..255 기본값: 0 (명시적 줄 바꿈 없음)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


자식 요소 가져오기

**반환값:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps