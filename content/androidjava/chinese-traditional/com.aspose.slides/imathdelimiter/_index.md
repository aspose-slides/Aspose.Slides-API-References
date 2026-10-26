---
title: IMathDelimiter
second_title: Aspose.Slides for Android via Java API 參考
description: 指定分隔符物件，由開啟和關閉字元組成，例如括號、花括號、方括號和直條，且內部包含一個或多個以指定字元分隔的數學元素。
type: docs
url: /zh-hant/com.aspose.slides/imathdelimiter/
---
**已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

指定分隔符物件，由開啟和關閉字元（例如括號、花括號、方括號和直條）組成，且內部包含一個或多個以指定字元分隔的數學元素。範例：(\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getArguments()](#getArguments--) | 一個或多個以分隔符字元分隔的數學元素 |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character 指定開始或開啟的分隔符字元。 |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character 指定開始或開啟的分隔符字元。 |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character 指定在分隔符物件中分隔參數的字元。 |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character 指定在分隔符物件中分隔參數的字元。 |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character 指定結束或關閉的分隔符字元。 |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character 指定結束或關閉的分隔符字元。 |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter 當 true 時，分隔符垂直增長以匹配其運算元的高度。 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter 當 true 時，分隔符垂直增長以匹配其運算元的高度。 |
| [getDelimiterShape()](#getDelimiterShape--) | 指定分隔符物件中分隔符的形狀。 |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | 指定分隔符物件中分隔符的形狀。 |
| [delimit(char separatorCharacter)](#delimit-char-) | 使用指定的分隔符字元分隔參數 |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


一個或多個以分隔符字元分隔的數學元素

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**返回：**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```


Delimiter Beginning Character 指定開始或開啟的分隔符字元。數學分隔符是諸如括號、方括號和大括號等包圍字元。預設值： '('。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**返回：**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```


Delimiter Beginning Character 指定開始或開啟的分隔符字元。數學分隔符是諸如括號、方括號和大括號等包圍字元。預設值： '('。

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
public abstract char getSeparatorCharacter()
```


Delimiter Separator Character 指定在分隔符物件中分隔參數的字元。預設：'|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**返回：**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```


Delimiter Separator Character 指定在分隔符物件中分隔參數的字元。預設：'|'.

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
public abstract char getEndingCharacter()
```


Delimiter Ending Character 指定結束或關閉的分隔符字元。數學分隔符是諸如括號、方括號和大括號等包圍字元。預設值： ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**返回：**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```


Delimiter Ending Character 指定結束或關閉的分隔符字元。數學分隔符是諸如括號、方括號和大括號等包圍字元。預設值： ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```


Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter 當 true 時，分隔符垂直增長以匹配其運算元的高度。預設值為 true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**返回：**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter 當 true 時，分隔符垂直增長以匹配其運算元的高度。預設值為 true

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
public abstract int getDelimiterShape()
```


指定分隔符物件中分隔符的形狀。當 MathDelimiterShape.Centered 時，分隔符會圍繞數學文字的軸心置中，且仍可調整以符合其內容的整體高度。當 MathDelimiterShape.Match 時，分隔符的高度和形狀會被更改以完全匹配其內容。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**返回：**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```


指定分隔符物件中分隔符的形狀。當 MathDelimiterShape.Centered 時，分隔符會圍繞數學文字的軸心置中，且仍可調整以符合其內容的整體高度。當 MathDelimiterShape.Match 時，分隔符的高度和形狀會被更改以完全匹配其內容。

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
public abstract IMathDelimiter delimit(char separatorCharacter)
```


使用指定的分隔符字元分隔參數

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separatorCharacter | char | 分隔符字元 |

**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 套用分隔符字元後的此物件