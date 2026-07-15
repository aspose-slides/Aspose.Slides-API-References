---
title: IMathBlock
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 指定一個包含於 MathParagraph 且自行換行的數學文字實例。
type: docs
url: /zh-hant/com.aspose.slides/imathblock/
---
**所有已實作的介面:**  
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

指定一個位於 MathParagraph 內且自行換行的數學文字實例。所有數學區域，包括方程式、運算式、方程式或運算式的陣列，以及公式，都以數學區塊表示。

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
>  ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | 使用分隔字元（不含括號）分隔所有子元素 |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | 將此區塊的子元素以指定的字元（如括號或其他）作為框架，並以分隔字元分隔 |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | 將另一個數學區塊與此區塊合併 |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 將此 [IMathBlock](../../com.aspose.slides/imathblock) 的內容儲存為 MathML |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

使用分隔字元（不含括號）分隔所有子元素

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
>  ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| separatorCharacter | char | 用作分隔的字元 |

**傳回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - IMathDelimiter 元素的實例

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

將此區塊的子元素以指定的字元（如括號或其他）作為框架，並以分隔字元分隔

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
>  ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| beginningCharacter | char | 開始字元（通常為左括號） |
| endingCharacter | char | 結束字元（通常為右括號） |
| separatorCharacter | char | 分隔字元 |

**傳回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 型別為 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的數學元素，包含指定的字元作為框架與分隔符

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | 要加入的區塊 |

**傳回值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 合併後的此數學區塊

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

將此 [IMathBlock](../../com.aspose.slides/imathblock) 的內容儲存為 MathML

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |