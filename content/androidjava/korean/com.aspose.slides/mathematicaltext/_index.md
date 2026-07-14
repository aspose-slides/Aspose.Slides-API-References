---
title: MathematicalText
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학 텍스트
type: docs
url: /ko/com.aspose.slides/mathematicaltext/
---
**상속:** java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**모든 구현된 인터페이스:**  
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

| 생성자 | 설명 |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | 기본 생성자 (String.Empty 값을 생성) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | 단일 기호로 MathText 생성 |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | 텍스트에서 MathematicalText 생성 |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 텍스트와 형식 설정으로 MathematicalText 생성 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getValue()](#getValue--) | 텍스트 값 |
| [setValue(String value)](#setValue-java.lang.String-) | 텍스트 값 |
| [getFormat()](#getFormat--) | 텍스트 서식 속성 |
| [getChildren()](#getChildren--) | 자식 요소 가져오기 |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```

기본 생성자 (String.Empty 값을 생성)

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
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 텍스트 값 |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```

텍스트와 형식 설정으로 MathematicalText 생성

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
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

자식 요소 가져오기

**반환값:**  
com.aspose.slides.IMathElement[]