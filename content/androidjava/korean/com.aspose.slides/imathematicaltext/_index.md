---
title: IMathematicalText
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학 텍스트
type: docs
url: /ko/com.aspose.slides/imathematicaltext/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

수학 텍스트

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getValue()](#getValue--) | 텍스트 값 |
| [setValue(String value)](#setValue-java.lang.String-) | 텍스트 값 |
| [getFormat()](#getFormat--) | 텍스트 서식 속성 |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
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