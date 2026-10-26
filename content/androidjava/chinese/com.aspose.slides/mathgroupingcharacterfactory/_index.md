---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建数学分组字符
type: docs
url: /zh/com.aspose.slides/mathgroupingcharacterfactory/
---
**继承:**  
java.lang.Object

**所有已实现的接口:**  
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)  
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

允许创建数学分组字符

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) |  |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) |  |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

创建数学分组字符

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用分组字符的数学元素 |
| character | char | 分组字符 |
| position | int | 分组字符的位置 |
| verticalJustification | int | 垂直对齐 |

**返回:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新的分组字符元素
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

创建数学分组字符

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用分组字符的数学元素 |

**返回:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新的分组字符元素