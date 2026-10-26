---
title: IMathBlock
second_title: Aspose.Slides for Java API 參考
description: 指定位於 MathParagraph 內部且自行佔一行的數學文字實例。
type: docs
url: /zh-hant/com.aspose.slides/imathblock/
---
**所有已實作介面:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

指定位於 MathParagraph 內部且自行佔一行的數學文字實例。所有數學區域，包括方程式、表達式、方程式或表達式的陣列以及公式，皆以 math block 方式表示。

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | 以分隔符號界定所有子元素（不含括號） |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | 將此區塊的子元素以指定的字元（例如括號或其他）作為框架，並以分隔符號界定 |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | 將另一個數學區塊與此區塊合併 |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 將此 [IMathBlock](../../com.aspose.slides/imathblock) 的內容儲存為 MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

以分隔符號界定所有子元素（不含括號）

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separatorCharacter | char | 用作分隔符號的字元 |

**返回:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - IMathDelimiter 元素的實例
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

將此區塊的子元素以指定的字元（例如括號或其他）作為框架，並以分隔符號界定

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char | 起始字元（通常為左括號） |
| endingCharacter | char | 結束字元（通常為右括號） |
| separatorCharacter | char | 分隔字元 |

**返回:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 類型為 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的數學元素，包含指定的字元作為框架與分隔符號
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

將另一個數學區塊與此區塊合併

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | 加入的區塊 |

**返回:**
[IMathBlock](../../com.aspose.slides/imathblock) - 合併後的此數學區塊
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

將此 [IMathBlock](../../com.aspose.slides/imathblock) 的內容儲存為 MathML

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |