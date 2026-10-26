---
title: MathGroupingCharacter
second_title: Aspose.Slides for Java API 参考
description: 指定一个位于表达式上方或下方的分组符号，通常用于突出元素之间的关系
type: docs
url: /zh/com.aspose.slides/mathgroupingcharacter/
---
**继承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

指定一个位于表达式上方或下方的分组符号，通常用于突出元素之间的关系

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | 使用默认分组字符 U+23DF（BOTTOM CURLY BRACKET）初始化 MathGroupingCharacter 类的新实例 |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | 初始化 MathGroupingCharacter 类的新实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基础参数 |
| [getCharacter()](#getCharacter--) | 分组字符 默认值：U+23DF（BOTTOM CURLY BRACKET） |
| [setCharacter(char value)](#setCharacter-char-) | 分组字符 默认值：U+23DF（BOTTOM CURLY BRACKET） |
| [getPosition()](#getPosition--) | 分组字符的位置。 |
| [setPosition(int value)](#setPosition-int-) | 分组字符的位置。 |
| [getVerticalJustification()](#getVerticalJustification--) | 组字符的垂直对齐方式。 |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | 组字符的垂直对齐方式。 |
| [getChildren()](#getChildren--) | 获取子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字符属性 |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

使用默认分组字符 U+23DF（BOTTOM CURLY BRACKET）初始化 MathGroupingCharacter 类的新实例

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 应用于条形的基础元素 |
### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

初始化 MathGroupingCharacter 类的新实例

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 应用于条形的基础元素 |
| character | char | 分组字符 |
| position | int | 分组字符的位置 |
| verticalJustification | int | 组字符的垂直对齐方式 |
### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基础参数

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
public final char getCharacter()
```

分组字符 默认值：U+23DF（BOTTOM CURLY BRACKET）

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部括号
> ```

**返回值:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

分组字符 默认值：U+23DF（BOTTOM CURLY BRACKET）

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部括号
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char |  |
### getPosition() {#getPosition--}
```
public final int getPosition()
```

分组字符的位置。默认：Bottom

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
public final void setPosition(int value)
```

分组字符的位置。默认：Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

组字符的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线上；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线上。默认：Position=Top 时为 Bottom，Position=Bottom 时为 Top

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
public final void setVerticalJustification(int value)
```

组字符的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线上；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线上。默认：Position=Top 时为 Bottom，Position=Bottom 时为 Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**返回值:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字符属性

**返回值:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps