---
title: MathDelimiter
second_title: Aspose.Slides for Android 之 Java API 參考
description: 指定分隔符物件，由開啟與關閉字元（如括號、花括號、方括號及直線）以及內部以指定字元分隔的一個或多個數學元素組成。
type: docs
url: /zh-hant/com.aspose.slides/mathdelimiter/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有實作的介面：**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

指定分隔符物件，由開啟與關閉字元（例如括號、花括號、方括號與直線）以及一個或多個以指定字元分隔的數學元素組成。範例：(\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## 建構函式

| 建構子 | 說明 |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | 使用指定的元素作為單一基礎參數初始化 MathDelimiter |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getArguments()](#getArguments--) | 以分隔符字元分隔一個或多個數學元素 |
| [getBeginningCharacter()](#getBeginningCharacter--) | 分隔符起始字元指定起始或開啟的分隔符字元。 |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | 分隔符起始字元指定起始或開啟的分隔符字元。 |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | 分隔符分隔字元指定在分隔符物件中分隔參數的字元。 |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | 分隔符分隔字元指定在分隔符物件中分隔參數的字元。 |
| [getEndingCharacter()](#getEndingCharacter--) | 分隔符結束字元指定結束或關閉的分隔符字元。 |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | 分隔符結束字元指定結束或關閉的分隔符字元。 |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長。當為 true 時，分隔符會垂直成長以匹配其運算元高度。 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長。當為 true 時，分隔符會垂直成長以匹配其運算元高度。 |
| [getDelimiterShape()](#getDelimiterShape--) | 指定分隔符物件中分隔符的形狀。 |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | 指定分隔符物件中分隔符的形狀。 |
| [delimit(char separatorCharacter)](#delimit-char-) | 使用指定的分隔符字元分隔參數 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 使用指定字元（如括號或其他字元）將數學元素包圍起來 |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字元屬性 |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

使用指定的元素作為單一基礎參數初始化 MathDelimiter

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用分隔符的基礎元素。可以為 null。 |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

以分隔符字元分隔一個或多個數學元素

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**傳回值：**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

分隔符起始字元指定起始或開啟的分隔符字元。數學分隔符是括號、方括號與花括號等包圍字元。預設值：'('。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**傳回值：**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

分隔符起始字元指定起始或開啟的分隔符字元。數學分隔符是括號、方括號與花括號等包圍字元。預設值：'('。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

分隔符分隔字元指定在分隔符物件中分隔參數的字元。預設值：'|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**傳回值：**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

分隔符分隔字元指定在分隔符物件中分隔參數的字元。預設值：'|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

分隔符結束字元指定結束或關閉的分隔符字元。數學分隔符是括號、方括號與花括號等包圍字元。預設值：')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**傳回值：**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

分隔符結束字元指定結束或關閉的分隔符字元。數學分隔符是括號、方括號與花括號等包圍字元。預設值：')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長。當為 true 時，分隔符會垂直成長以匹配其運算元高度。預設值為 true

--------------------

> ```
> 範例：
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**傳回值：**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長。當為 true 時，分隔符會垂直成長以匹配其運算元高度。預設值為 true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

指定分隔符物件中分隔符的形狀。當為 MathDelimiterShape.Centered 時，分隔符會以數學文字的軸心居中，且仍會調整以符合其內容的整體高度。當為 MathDelimiterShape.Match 時，分隔符的高度與形狀會被調整以完全匹配其內容。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**傳回值：**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

指定分隔符物件中分隔符的形狀。當為 MathDelimiterShape.Centered 時，分隔符會以數學文字的軸心居中，且仍會調整以符合其內容的整體高度。當為 MathDelimiterShape.Match 時，分隔符的高度與形狀會被調整以完全匹配其內容。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

使用指定的分隔符字元分隔參數

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separatorCharacter | char | 分隔符字元 |

**傳回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 套用分隔符字元後的此物件
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

使用指定字元（如括號或其他字元）將數學元素包圍起來

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char | 起始字元（通常為左括號） |
| endingCharacter | char | 結束字元（通常為右括號） |

**傳回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 若 beginningCharacter 與 endingCharacter 為 null，僅為相應屬性指派值且不會建立新物件（傳回此實例）。否則，傳回以指定字元作為框架且此 [MathDelimiter](../../com.aspose.slides/mathdelimiter) 實例被包圍在內的新 Delimiter 數學元素。
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**傳回值：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字元屬性

**傳回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps