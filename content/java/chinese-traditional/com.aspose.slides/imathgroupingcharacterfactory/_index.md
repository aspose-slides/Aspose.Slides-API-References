---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: 允許建立數學群組字元
type: docs
url: /zh-hant/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

允許建立數學群組字元

--------------------

用於 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | 建立數學群組字元 |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | 建立數學群組字元 |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

建立數學群組字元

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用群組字元的數學元素 |
| character | char | 群組字元 |
| position | int | 群組字元的位置 |
| verticalJustification | int | 垂直對齊方式 |

**傳回值：**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新的群組字元元素
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

建立數學群組字元

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用群組字元的數學元素 |

**傳回值：**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新的群組字元元素