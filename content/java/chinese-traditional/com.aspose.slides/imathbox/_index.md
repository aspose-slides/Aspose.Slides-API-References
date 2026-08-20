---
title: IMathBox
second_title: Aspose.Slides for Java API 參考文件
description: 指定數學元素的邏輯盒裝包裝。
type: docs
url: /zh-hant/com.aspose.slides/imathbox/
---
**所有已實作介面:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

指定數學元素的邏輯盒裝（包裝）。例如，盒裝物件可以作為具有或不具有對齊點的操作符模擬器，作為換行點，或被分組以避免在其內部換行。例如，"==" 運算子應該被盒裝以防止換行。

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getOperatorEmulator()](#getOperatorEmulator--) | 操作符模擬器。 |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | 操作符模擬器。 |
| [getNoBreak()](#getNoBreak--) | 不換行。 |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | 不換行。 |
| [getDifferential()](#getDifferential--) | 微分。 |
| [setDifferential(boolean value)](#setDifferential-boolean-) | 微分。 |
| [getAlignmentPoint()](#getAlignmentPoint--) | 當為 true 時，此操作符模擬器充當對齊點；即其他方程式中指定的對齊點可以與之對齊。 |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | 當為 true 時，此操作符模擬器充當對齊點；即其他方程式中指定的對齊點可以與之對齊。 |
| [getExplicitBreak()](#getExplicitBreak--) | 明確換行指定在 Box 物件的起始位置是否有換行，使得行在盒子起始處換行。 |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | 明確換行指定在 Box 物件的起始位置是否有換行，使得行在盒子起始處換行。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基礎參數

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
>  ```

**返回值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```


操作符模擬器。當為 true 時，盒子及其內容會作為單一操作符並繼承操作符的屬性。這表示，例如，該字符可以作為換行點，且可與其他操作符對齊。操作符模擬器常用於多個字形組合成一個操作符的情況，例如 '=='. 預設值：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**返回值:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```


操作符模擬器。當為 true 時，盒子及其內容會作為單一操作符並繼承操作符的屬性。這表示，例如，該字符可以作為換行點，且可與其他操作符對齊。操作符模擬器常用於多個字形組合成一個操作符的情況，例如 '=='. 預設值：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```


不換行。此屬性指定物件盒的「不可斷行」屬性。當為 true 時，盒子內部不會發生換行。這在包含多個二元運算子的操作符模擬器中可能很重要。若未指定此元素，盒子內部可發生換行。預設：true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**返回值:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```


不換行。此屬性指定物件盒的「不可斷行」屬性。當為 true 時，盒子內部不會發生換行。這在包含多個二元運算子的操作符模擬器中可能很重要。若未指定此元素，盒子內部可發生換行。預設：true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```


微分。當為 true 時，盒子作為微分（例如積分被積項中的 \\ud835\\udc51\\ud835\\udc65），並獲得適當的水平間距。預設：false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**返回值:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```


微分。當為 true 時，盒子作為微分（例如積分被積項中的 \\ud835\\udc51\\ud835\\udc65），並獲得適當的水平間距。預設：false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```


當為 true 時，此操作符模擬器充當對齊點；即其他方程式中指定的對齊點可以與之對齊。預設：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**返回值:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```


當為 true 時，此操作符模擬器充當對齊點；即其他方程式中指定的對齊點可以與之對齊。預設：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```


明確換行指定在 Box 物件的起始位置是否有換行，使得行在盒子起始處換行。指定前一行數學文字中的運算子編號，該編號將作為當前行數學文字的對齊點。可能的值：1..255。預設：0（無明確換行）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**返回值:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```


明確換行指定在 Box 物件的起始位置是否有換行，使得行在盒子起始處換行。指定前一行數學文字中的運算子編號，該編號將作為當前行數學文字的對齊點。可能的值：1..255。預設：0（無明確換行）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |