---
title: IMathBox
second_title: Aspose.Slides for Android via Java API 參考
description: 指定數學元素的邏輯盒裝封裝。
type: docs
url: /zh-hant/com.aspose.slides/imathbox/
---
**所有已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

指定數學元素的邏輯盒裝（封裝）。例如，盒狀物件可以作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以避免在其中換行。舉例來說，應將 "==" 運算子盒裝起來以防止換行。

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | 不換行。 |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | 不換行。 |
| [getDifferential()](#getDifferential--) | 微分。 |
| [setDifferential(boolean value)](#setDifferential-boolean-) | 微分。 |
| [getAlignmentPoint()](#getAlignmentPoint--) | 當為 true 時，此運算子模擬器充當對齊點；也就是說，其他方程式中指定的對齊點可以與之對齊。 |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | 當為 true 時，此運算子模擬器充當對齊點；也就是說，其他方程式中指定的對齊點可以與之對齊。 |
| [getExplicitBreak()](#getExplicitBreak--) | 明確換行指定是否在 Box 物件的起始處有換行，使得行在該盒子的起始處換行。 |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | 明確換行指定是否在 Box 物件的起始處有換行，使得行在該盒子的起始處換行。 |

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
> ```

**傳回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Operator Emulator. 當為 true 時，該盒子及其內容表現為單一運算子，並繼承運算子的屬性。這表示，例如，該字元可以作為換行點，且可以對齊至其他運算子。當一個或多個字形結合形成運算子（例如 '=='）時，常會使用 Operator Emulator。Default value: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```


**傳回值：**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Operator Emulator. 當為 true 時，該盒子及其內容表現為單一運算子，並繼承運算子的屬性。這表示，例如，該字元可以作為換行點，且可以對齊至其他運算子。當一個或多個字形結合形成運算子（例如 '=='）時，常會使用 Operator Emulator。Default value: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

不換行。此屬性指定物件盒的「不可分割」屬性。當為 true 時，盒內不能發生換行。對於由多個二元運算子組成的 Operator Emulator，這可能很重要。若未指定此元素，則盒內可發生換行。Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```


**傳回值：**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

不換行。此屬性指定物件盒的「不可分割」屬性。當為 true 時，盒內不能發生換行。對於由多個二元運算子組成的 Operator Emulator，這可能很重要。若未指定此元素，則盒內可發生換行。Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

微分。當為 true 時，盒子作為微分（例如 \\ud835\\udc51\\ud835\\udc65 出現在被積函數中），並獲得適當的水平間距以符合數學微分的排版。Default: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**傳回值：**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

微分。當為 true 時，盒子作為微分（例如 \\ud835\\udc51\\ud835\\udc65 出現在被積函數中），並獲得適當的水平間距以符合數學微分的排版。Default: false

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

當為 true 時，此運算子模擬器充當對齊點；也就是說，其他方程式中指定的對齊點可以與之對齊。Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**傳回值：**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

當為 true 時，此運算子模擬器充當對齊點；也就是說，其他方程式中指定的對齊點可以與之對齊。Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

明確換行指定是否在 Box 物件的起始處有換行，使得行在該盒子的起始處換行。指定前一行數學文字中用作本行對齊點的運算子編號。可能的值：1..255 Default: 0 (no explicit break)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**傳回值：**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

明確換行指定是否在 Box 物件的起始處有換行，使得行在該盒子的起始處換行。指定前一行數學文字中用作本行對齊點的運算子編號。可能的值：1..255 Default: 0 (no explicit break)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |