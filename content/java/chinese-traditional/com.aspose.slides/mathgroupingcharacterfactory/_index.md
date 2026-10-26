---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides for Java API 參考
description: 允許建立數學分組字元
type: docs
url: /zh-hant/com.aspose.slides/mathgroupingcharacterfactory/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)  
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

允許建立數學分組字元

--------------------

供 COM 相容性使用  
## 建構函式

| 建構式 | 說明 |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | 建立數學分組字元 |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | 建立數學分組字元 |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

建立數學分組字元

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用分組字元的數學元素 |
| character | char | 分組字元 |
| position | int | 分組字元的位置 |
| verticalJustification | int | 垂直對齊方式 |

**傳回值:**  
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新的分組字元元素
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

建立數學分組字元

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用分組字元的數學元素 |

**傳回值:**  
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新的分組字元元素