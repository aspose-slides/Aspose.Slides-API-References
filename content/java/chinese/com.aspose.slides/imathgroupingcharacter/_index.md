---
title: IMathGroupingCharacter
second_title: Aspose.Slides Java API 参考
description: 指定表达式上方或下方的分组符号，通常用于突出元素之间的关系
type: docs
url: /zh/com.aspose.slides/imathgroupingcharacter/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

指定表达式上方或下方的分组符号，通常用于突出元素之间的关系

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## 方法

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | 基参数 |
| [getCharacter()](#getCharacter--) | 分组字符 默认值：U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | 分组字符 默认值：U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | 分组字符的位置。 |
| [setPosition(int value)](#setPosition-int-) | 分组字符的位置。 |
| [getVerticalJustification()](#getVerticalJustification--) | 分组字符的垂直对齐方式。 |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | 分组字符的垂直对齐方式。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基参数

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**返回值:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

分组字符 默认值：U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部圆括号
> ```

**返回值:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

分组字符 默认值：U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部圆括号
> ```

**参数:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

分组字符的位置。默认值：Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**返回值:**  
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

分组字符的位置。默认值：Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**参数:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

分组字符的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当分组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线。默认：Bottom（当 Position=Top 时），Top（当 Position=Bottom 时）

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**返回值:**  
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

分组字符的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当分组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线。默认：Bottom（当 Position=Top 时），Top（当 Position=Bottom 时）

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**参数:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |