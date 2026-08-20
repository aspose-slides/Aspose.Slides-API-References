---
title: MathBox
second_title: Aspose.Slides for Java API 參考文件
description: 指定數學元素的邏輯盒裝封裝。
type: docs
url: /zh-hant/com.aspose.slides/mathbox/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有已實作的介面：**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

指定數學元素的邏輯盒裝（封裝）。例如，盒裝物件可以作為具有或不具有對齊點的運算子模擬器，作為換行點，或被分組以避免在盒內換行。例如，"==" 運算子應該盒裝，以防止換行。

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | 使用指定的元素作為參數初始化 MathBox |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基本參數 |
| [getOperatorEmulator()](#getOperatorEmulator--) | 運算子模擬器。 |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | 運算子模擬器。 |
| [getNoBreak()](#getNoBreak--) | 不換行 此屬性指定物件框的 "unbreakable" 屬性。 |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | 不換行 此屬性指定物件框的 "unbreakable" 屬性。 |
| [getDifferential()](#getDifferential--) | 微分 當為 true 時，盒子充當微分符號（例如，\\ud835\\udc51\\ud835\\udc65 在積分項中），並取得適當的水平間距。 |
| [setDifferential(boolean value)](#setDifferential-boolean-) | 微分 當為 true 時，盒子充當微分符號（例如，\\ud835\\udc51\\ud835\\udc65 在積分項中），並取得適當的水平間距。 |
| [getAlignmentPoint()](#getAlignmentPoint--) | 當為 true 時，此運算子模擬器充當對齊點；即其他方程式中指定的對齊點可以與之對齊。 |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | 當為 true 時，此運算子模擬器充當對齊點；即其他方程式中指定的對齊點可以與之對齊。 |
| [getExplicitBreak()](#getExplicitBreak--) | 明確換行 指定在 Box 物件起始處是否有換行，以使行在盒子起始處換行。 |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | 明確換行 指定在 Box 物件起始處是否有換行，以使行在盒子起始處換行。 |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字元屬性 |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

使用指定的元素作為參數初始化 MathBox

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用於盒子的基礎元素。可為 null。 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基本參數

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

運算子模擬器。當為 true 時，盒子及其內容行為如同單一運算子，並繼承運算子的屬性。這表示，例如，字元可以作為換行點，並可對齊至其他運算子。運算子模擬器常用於多個字形組合成單一運算子（如 '=='）的情況。預設值：false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**返回值：**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

運算子模擬器。當為 true 時，盒子及其內容行為如同單一運算子，並繼承運算子的屬性。這表示，例如，字元可以作為換行點，並可對齊至其他運算子。運算子模擬器常用於多個字形組合成單一運算子（如 '=='）的情況。預設值：false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

不換行 此屬性指定物件框的 "unbreakable" 屬性。當為 true 時，盒子內部不得換行。對於由多個二元運算子組成的運算子模擬器此屬性特別重要。若未指定此屬性，盒子內可發生換行。預設：true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**返回值：**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

不換行 此屬性指定物件框的 "unbreakable" 屬性。當為 true 時，盒子內部不得換行。對於由多個二元運算子組成的運算子模擬器此屬性特別重要。若未指定此屬性，盒子內可發生換行。預設：true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

微分 當為 true 時，盒子充當微分符號（例如，\\ud835\\udc51\\ud835\\udc65 在積分項中），並取得適當的水平間距。預設：false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**返回值：**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

微分 當為 true 時，盒子充當微分符號（例如，\\ud835\\udc51\\ud835\\udc65 在積分項中），並取得適當的水平間距。預設：false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

當為 true 時，此運算子模擬器充當對齊點；即其他方程式中指定的對齊點可以與之對齊。預設：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**返回值：**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

當為 true 時，此運算子模擬器充當對齊點；即其他方程式中指定的對齊點可以與之對齊。預設：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

明確換行 指定在 Box 物件起始處是否有換行，以使行在盒子起始處換行。指定前一行數學文字中作為當前行對齊點之運算子的編號。可能的值：1..255。預設：0（無明確換行）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**返回值：**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

明確換行 指定在 Box 物件起始處是否有換行，以使行在盒子起始處換行。指定前一行數學文字中作為當前行對齊點之運算子的編號。可能的值：1..255。預設：0（無明確換行）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**返回值：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字元屬性

**返回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps