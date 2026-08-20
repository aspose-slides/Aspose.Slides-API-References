---
title: MathematicalText
second_title: Aspose.Slides for Java API 레퍼런스
description: 수학 텍스트
type: docs
url: /ko/com.aspose.slides/mathematicaltext/
---
**상속:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)  
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

수학 텍스트

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## 생성자

| Constructor | Description |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | 기본 생성자(String.Empty 값을 생성) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | 단일 기호로 MathText 생성 |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | 텍스트에서 MathematicalText 생성 |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 텍스트와 형식 설정에서 MathematicalText 생성 |
## 메서드

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | 텍스트 값 |
| [setValue(String value)](#setValue-java.lang.String-) | 텍스트 값 |
| [getFormat()](#getFormat--) | 텍스트 서식 속성 |
| [getChildren()](#getChildren--) | 하위 요소 가져오기 |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


기본 생성자(String.Empty 값을 생성)

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```


### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```


단일 기호로 MathText 생성

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | 단일 기호 |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


텍스트에서 MathematicalText 생성

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | 텍스트 값 |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


텍스트와 형식 설정에서 MathematicalText 생성

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | 텍스트 값 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 텍스트 형식 설정 |

### getValue() {#getValue--}
```
public final String getValue()
```


텍스트 값

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**반환값:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


텍스트 값

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


텍스트 서식 속성

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```


**반환값:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


하위 요소 가져오기

**반환값:**
com.aspose.slides.IMathElement[]