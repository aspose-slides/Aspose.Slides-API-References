---
title: MathArray
second_title: Aspose.Slides 針對 Android 的 Java API 參考
description: 指定一個垂直排列的方程式或任何數學物件
type: docs
url: /zh-hant/com.aspose.slides/matharray/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有實作的介面：**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

指定一個垂直排列的方程式或任何數學物件陣列

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | 建立數學陣列並將指定的元素放入其中 |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | 建立數學陣列並將指定的元素放入其中 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getArguments()](#getArguments--) | 陣列的項目集合 |
| [getBaseJustification()](#getBaseJustification--) | 指定陣列相對於周圍文字的對齊方式。陣列外的文字可與陣列物件的底部、頂部或中心對齊。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定陣列相對於周圍文字的對齊方式。陣列外的文字可與陣列物件的底部、頂部或中心對齊。 |
| [getMaximumDistribution()](#getMaximumDistribution--) | 最大分布：當值為 true 時，陣列會間距至其包含元素（頁面、欄、儲存格等）的最大寬度。 |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | 最大分布：當值為 true 時，陣列會間距至其包含元素（頁面、欄、儲存格等）的最大寬度。 |
| [getObjectDistribution()](#getObjectDistribution--) | 物件分布：當值為 true 時，陣列的內容會間距至陣列物件的最大寬度。 |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | 物件分布：當值為 true 時，陣列的內容會間距至陣列物件的最大寬度。 |
| [getRowSpacingRule()](#getRowSpacingRule--) | 陣列元素之垂直間距類型，預設值：SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 陣列元素之垂直間距類型，預設值：SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | 陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用；若為 Exactly，則計量單位為點；若為 Multiple，則計量單位為半行。 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用；若為 Exactly，則計量單位為點；若為 Multiple，則計量單位為半行。 |
| [getChildren()](#getChildren--) | 取得子元素 |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```


建立數學陣列並將指定的元素放入其中

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要放入陣列的元素 |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```


建立數學陣列並將指定的元素放入其中

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | 要放入陣列的元素 |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


陣列的項目集合

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**返回值：**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


指定陣列相對於周圍文字的對齊方式。陣列外的文字可與陣列物件的底部、頂部或中心對齊。預設值：Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**返回值：**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```


指定陣列相對於周圍文字的對齊方式。陣列外的文字可與陣列物件的底部、頂部或中心對齊。預設值：Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```


最大分布：當值為 true 時，陣列會間距至其包含元素（頁面、欄、儲存格等）的最大寬度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**返回值：**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```


最大分布：當值為 true 時，陣列會間距至其包含元素（頁面、欄、儲存格等）的最大寬度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```


物件分布：當值為 true 時，陣列的內容會間距至陣列物件的最大寬度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**返回值：**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```


物件分布：當值為 true 時，陣列的內容會間距至陣列物件的最大寬度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```


陣列元素之垂直間距類型，預設值：SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**返回值：**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```


陣列元素之垂直間距類型，預設值：SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```


陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用；若為 Exactly，則計量單位為點；若為 Multiple，則計量單位為半行。預設值：0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**返回值：**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```


陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用；若為 Exactly，則計量單位為點；若為 Multiple，則計量單位為半行。預設值：0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


取得子元素

**返回值：**
com.aspose.slides.IMathElement[]