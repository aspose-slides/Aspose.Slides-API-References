---
title: IMathPhantom
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 자식 요소의 레이아웃에 영향을 주지만 반드시 표시하지는 않는 팬텀 수학 객체 ltmphantgt를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imathphantom/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Represents a phantom math object (<m:phant>) that affects the layout of its child element without necessarily displaying it. A phantom can hide its base expression while preserving its width, height, or depth to align formulas or reserve space. Visibility and geometry behavior are controlled by properties such as Show, ZeroWid, ZeroAsc, ZeroDesc, and Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // 내용 숨기기
>  phantom.setZeroWidth(false);     // 너비 유지
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getShow()](#getShow--) | 기본 요소가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setShow(boolean value)](#setShow-boolean-) | 기본 요소가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getZeroWidth()](#getZeroWidth--) | 기본 요소의 너비를 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 기본 요소의 너비를 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getZeroAsc()](#getZeroAsc--) | 기본 요소의 상승(기준선 위 높이)을 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 기본 요소의 상승(기준선 위 높이)을 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getZeroDesc()](#getZeroDesc--) | 기본 요소의 하강(기준선 아래 깊이)을 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 기본 요소의 하강(기준선 아래 깊이)을 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getTransp()](#getTransp--) | 클래스 기반 간격 규칙에 대해 팬텀이 투명한지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setTransp(boolean value)](#setTransp-boolean-) | 클래스 기반 간격 규칙에 대해 팬텀이 투명한지 여부를 나타내는 값을 가져오거나 설정합니다. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract boolean getShow()
```


기본 요소가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

false인 경우, 기본 요소는 숨겨지지만 다른 팬텀 설정에 따라 여전히 공간을 차지할 수 있습니다. OMML 속성 m:show에 해당합니다.

**반환값:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```


기본 요소가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

false인 경우, 기본 요소는 숨겨지지만 다른 팬텀 설정에 따라 여전히 공간을 차지할 수 있습니다. OMML 속성 m:show에 해당합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```


기본 요소의 너비를 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

true인 경우, 팬텀이 기본에 대한 가로 공간을 예약하지 않습니다. OMML 속성 m:zeroWid에 해당합니다.

**반환값:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```


기본 요소의 너비를 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

true인 경우, 팬텀이 기본에 대한 가로 공간을 예약하지 않습니다. OMML 속성 m:zeroWid에 해당합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```


기본 요소의 상승(기준선 위 높이)을 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

true인 경우, 팬텀이 주변 수학 행의 기준선을 올리지 않습니다. OMML 속성 m:zeroAsc에 해당합니다.

**반환값:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```


기본 요소의 상승(기준선 위 높이)을 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

true인 경우, 팬텀이 주변 수학 행의 기준선을 올리지 않습니다. OMML 속성 m:zeroAsc에 해당합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```


기본 요소의 하강(기준선 아래 깊이)을 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

true인 경우, 팬텀이 주변 수학 행의 기준선을 낮추지 않습니다. OMML 속성 m:zeroDesc에 해당합니다.

**반환값:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```


기본 요소의 하강(기준선 아래 깊이)을 0으로 처리해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

true인 경우, 팬텀이 주변 수학 행의 기준선을 낮추지 않습니다. OMML 속성 m:zeroDesc에 해당합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```


클래스 기반 간격 규칙에 대해 팬텀이 투명한지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

true인 경우, 팬텀 내부의 연산자와 기호는 여전히 팬텀 주변의 수학 간격에 영향을 줍니다(보이는 것처럼). false인 경우, 클래스 기반 간격이 무시됩니다. OMML 속성 m:transp에 해당합니다.

**반환값:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```


클래스 기반 간격 규칙에 대해 팬텀이 투명한지 여부를 나타내는 값을 가져오거나 설정합니다.

--------------------

true인 경우, 팬텀 내부의 연산자와 기호는 여전히 팬텀 주변의 수학 간격에 영향을 줍니다(보이는 것처럼). false인 경우, 클래스 기반 간격이 무시됩니다. OMML 속성 m:transp에 해당합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |