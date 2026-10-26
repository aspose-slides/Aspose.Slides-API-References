---
title: MathPhantom
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 팬텀 수학 객체 ltmphantgt를 나타내며, 자식 요소의 레이아웃에 영향을 주지만 반드시 표시되는 것은 아닙니다.
type: docs
url: /ko/com.aspose.slides/mathphantom/
---
**상속:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

팬텀 수학 객체(<m:phant>)를 나타내며, 자식 요소의 레이아웃에 영향을 주지만 반드시 표시되는 것은 아닙니다. 팬텀은 기본 수식을 숨기면서도 너비, 높이 또는 깊이를 유지하여 수식을 정렬하거나 공간을 예약할 수 있습니다. 가시성 및 기하학적 동작은 Show, ZeroWid, ZeroAsc, ZeroDesc, Transp와 같은 속성으로 제어됩니다.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // 내용 숨기기
>  phantom.setZeroWidth(false);     // 너비 유지
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | 지정된 기본 수학 요소를 사용하여 [MathPhantom](../../com.aspose.slides/mathphantom) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getShow()](#getShow--) | 기본 요소가 표시되는지를 나타내는 값을 가져오거나 설정합니다. |
| [setShow(boolean value)](#setShow-boolean-) | 기본 요소가 표시되는지를 나타내는 값을 가져오거나 설정합니다. |
| [getZeroWidth()](#getZeroWidth--) | 기본 요소의 너비를 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 기본 요소의 너비를 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다. |
| [getZeroAsc()](#getZeroAsc--) | 기본 요소의 상승(기준선 위 높이)을 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 기본 요소의 상승(기준선 위 높이)을 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다. |
| [getZeroDesc()](#getZeroDesc--) | 기본 요소의 하강(기준선 아래 깊이)을 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 기본 요소의 하강(기준선 아래 깊이)을 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다. |
| [getTransp()](#getTransp--) | 클래스 기반 간격 규칙에 대해 팬텀이 투명한지를 나타내는 값을 가져오거나 설정합니다. |
| [setTransp(boolean value)](#setTransp-boolean-) | 클래스 기반 간격 규칙에 대해 팬텀이 투명한지를 나타내는 값을 가져오거나 설정합니다. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다 |

### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

지정된 기본 수학 요소를 사용하여 [MathPhantom](../../com.aspose.slides/mathphantom) 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 팬텀에 의해 가시성과 레이아웃이 제어되는 기본 [IMathElement](../../com.aspose.slides/imathelement)입니다. 이 요소는 숨기거나 표시될 수 있는 내용을 정의하지만 주변 수학의 기하학적 정렬에 여전히 영향을 미칩니다. |

팬텀 요소는 기본 수식의 시각적 공간을 예약하거나 억제하기 위해 사용되며, 반드시 표시될 필요는 없습니다. 이는 OMML 요소 <m:phant>에 해당합니다. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

기본 인수

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

기본 요소가 표시되는지를 나타내는 값을 가져오거나 설정합니다.

--------------------

false일 경우, 기본 요소가 숨겨지지만 다른 팬텀 설정에 따라 여전히 공간을 차지할 수 있습니다. OMML 속성 m:show에 해당합니다.

**반환값:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

기본 요소가 표시되는지를 나타내는 값을 가져오거나 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

기본 요소의 너비를 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다.

--------------------

true일 경우, 팬텀은 기본 요소에 대한 수평 공간을 예약하지 않습니다. OMML 속성 m:zeroWid에 해당합니다.

**반환값:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

기본 요소의 너비를 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

기본 요소의 상승(기준선 위 높이)을 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다.

--------------------

true일 경우, 팬텀은 주변 수학 라인의 기준선을 올리지 않습니다. OMML 속성 m:zeroAsc에 해당합니다.

**반환값:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

기본 요소의 상승(기준선 위 높이)을 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

기본 요소의 하강(기준선 아래 깊이)을 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다.

--------------------

true일 경우, 팬텀은 주변 수학 라인의 기준선을 낮추지 않습니다. OMML 속성 m:zeroDesc에 해당합니다.

**반환값:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

기본 요소의 하강(기준선 아래 깊이)을 0으로 처리해야 하는지를 나타내는 값을 가져오거나 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

클래스 기반 간격 규칙에 대해 팬텀이 투명한지를 나타내는 값을 가져오거나 설정합니다.

--------------------

true일 경우, 팬텀 내부의 연산자와 기호는 팬텀 주변의 수학적 간격에 여전히 영향을 미칩니다(보이는 것처럼). false일 경우, 클래스 기반 간격이 무시됩니다. OMML 속성 m:transp에 해당합니다.

**반환값:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

클래스 기반 간격 규칙에 대해 팬텀이 투명한지를 나타내는 값을 가져오거나 설정합니다.

--------------------

true일 경우, 팬텀 내부의 연산자와 기호는 팬텀 주변의 수학적 간격에 여전히 영향을 미칩니다(보이는 것처럼). false일 경우, 클래스 기반 간격이 무시됩니다. OMML 속성 m:transp에 해당합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

자식 요소를 가져옵니다

**반환값:**
com.aspose.slides.IMathElement[]