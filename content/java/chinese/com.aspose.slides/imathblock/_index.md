---
title: IMathBlock
second_title: Aspose.Slides for Java API 参考
description: 指定一个包含在 MathParagraph 中并且独占一行的数学文本实例。
type: docs
url: /zh/com.aspose.slides/imathblock/
---
**所有实现的接口:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

指定一个包含在 MathParagraph 中并且独占一行的数学文本实例。所有数学区域，包括方程式、表达式、方程式或表达式数组以及公式，都由数学块表示。

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | 使用分隔字符（不含括号）分隔所有子元素 |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | 使用指定字符（如括号或其他字符）将此块的子元素框住，并使用分隔字符进行分隔 |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | 将另一个数学块与此块连接 |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 将此 [IMathBlock](../../com.aspose.slides/imathblock) 的内容保存为 MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

使用分隔字符（不含括号）分隔所有子元素

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```
**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| separatorCharacter | char | 用作分隔符的字符 |

**返回值:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - IMathDelimiter 元素的实例
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

使用指定字符（如括号或其他字符）将此块的子元素框住，并使用分隔字符进行分隔

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```
**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| beginningCharacter | char | 起始字符（通常为左括号） |
| endingCharacter | char | 结束字符（通常为右括号） |
| separatorCharacter | char | 分隔字符 |

**返回值:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 类型为 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的数学元素，其中包括指定字符作为框架和分隔符
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

将另一个数学块与此块连接

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```
**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | 要加入的块 |

**返回值:**
[IMathBlock](../../com.aspose.slides/imathblock) - 合并后的此数学块
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

将此 [IMathBlock](../../com.aspose.slides/imathblock) 的内容保存为 MathML

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |