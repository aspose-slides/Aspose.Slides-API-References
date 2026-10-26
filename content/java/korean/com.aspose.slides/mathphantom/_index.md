---
title: MathPhantom
second_title: Aspose.Slides for Java API 참조
description: 자식 요소의 레이아웃에 영향을 주지만 반드시 표시되지 않을 수 있는 phantom 수학 객체 ltmphantgt를 나타냅니다.
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

phantom 수학 객체 (<m:phant>)를 나타내며, 자식 요소의 레이아웃에 영향을 주지만 반드시 표시될 필요는 없습니다. phantom은 기본 표현식을 숨기면서도 너비, 높이 또는 깊이를 유지하여 수식을 정렬하거나 공간을 예약할 수 있습니다. 가시성 및 기하학 동작은 Show, ZeroWid, ZeroAsc, ZeroDesc 및 Transp와 같은 속성으로 제어됩니다.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // 내용을 숨깁니다
>  phantom.setZeroWidth(false);     // 폭을 유지합니다
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | [MathPhantom](../../com.aspose.slides/mathphantom) 클래스를 지정된 기본 수학 요소를 사용하여 새 인스턴스를 초기화합니다. |
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getShow()](#getShow--) | 기본 요소가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setShow(boolean value)](#setShow-boolean-) | 기본 요소가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getZeroWidth()](#getZeroWidth--) | 기본 요소의 너비를 0으로 처리할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 기본 요소의 너비를 0으로 처리할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getZeroAsc()](#getZeroAsc--) | 기본 요소의 상승(기준선 위 높이)을 0으로 처리할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 기본 요소의 상승(기준선 위 높이)을 0으로 처리할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getZeroDesc()](#getZeroDesc--) | 기본 요소의 하강(기준선 아래 깊이)을 0으로 처리할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 기본 요소의 하강(기준선 아래 깊이)을 0으로 처리할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getTransp()](#getTransp--) | phantom이 클래스 기반 간격 규칙에 대해 투명한지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setTransp(boolean value)](#setTransp-boolean-) | phantom이 클래스 기반 간격 규칙에 대해 투명한지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다 |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

[MathPhantom](../../com.aspose.slides/mathphantom) 클래스를 지정된 기본 수학 요소를 사용하여 새 인스턴스를 초기화합니다.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phantom에 의해 가시성과 레이아웃이 제어되는 기본 [IMathElement](../../com.aspose.slides/imathelement). 이 요소는 숨기거나 표시될 수 있는 내용을 정의하지만, 주변 수식의 기하학적 정렬에 여전히 영향을 줍니다. |

The phantom element is used to reserve or suppress the visual space of its base expression without necessarily displaying it. It corresponds to the OMML element <m:phant>.

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

기본 요소가 표시되는지 여부를 가져오거나 설정합니다.

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**반환값:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

기본 요소가 표시되는지 여부를 가져오거나 설정합니다.

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

기본 요소의 너비를 0으로 처리할지 여부를 가져오거나 설정합니다.

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**반환값:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

기본 요소의 너비를 0으로 처리할지 여부를 가져오거나 설정합니다.

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

기본 요소의 상승(기준선 위 높이)을 0으로 처리할지 여부를 가져오거나 설정합니다.

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**반환값:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

기본 요소의 상승(기준선 위 높이)을 0으로 처리할지 여부를 가져오거나 설정합니다.

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

기본 요소의 하강(기준선 아래 깊이)을 0으로 처리할지 여부를 가져오거나 설정합니다.

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**반환값:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

기본 요소의 하강(기준선 아래 깊이)을 0으로 처리할지 여부를 가져오거나 설정합니다.

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

phantom이 클래스 기반 간격 규칙에 대해 투명한지 여부를 가져오거나 설정합니다.

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**반환값:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

phantom이 클래스 기반 간격 규칙에 대해 투명한지 여부를 가져오거나 설정합니다.

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**매개변수:**
| 매개변수 | 형식 | 설명 |
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