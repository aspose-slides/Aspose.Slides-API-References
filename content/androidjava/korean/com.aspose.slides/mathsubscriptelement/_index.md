---
title: MathSubscriptElement
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 베이스와 오른쪽 아래에 배치된 축소된 크기의 아래첨자로 구성된 아래첨자 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/mathsubscriptelement/
---
**상속:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)  
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

베이스와 오른쪽 아래에 배치된 축소된 크기의 아래첨자를 포함하는 하위스크립트 객체를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathSubscriptElement 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSubscript()](#getSubscript--) | 아래첨자 |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다 |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```

MathSubscriptElement 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

아래첨자

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

자식 요소를 가져옵니다

**반환값:**
com.aspose.slides.IMathElement[]