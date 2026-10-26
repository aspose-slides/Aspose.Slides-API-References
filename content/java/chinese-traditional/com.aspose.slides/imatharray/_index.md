---
title: IMathArray
second_title: Aspose.Slides for Java API 參考
description: 指定一個包含方程式或任何數學物件的垂直陣列
type: docs
url: /zh-hant/com.aspose.slides/imatharray/
---
**已實作的介面:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

指定一個包含方程式或任何數學物件的垂直陣列

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getArguments()](#getArguments--) | 陣列的項目集合 |
| [getBaseJustification()](#getBaseJustification--) | 指定陣列相對於周圍文字的對齊方式。陣列外的文字可與陣列物件的底部、頂部或中心對齊。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定陣列相對於周圍文字的對齊方式。陣列外的文字可與陣列物件的底部、頂部或中心對齊。 |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution 當為 true 時，陣列會以包含元素（頁面、欄、儲存格等）的最大寬度進行間距配置。 |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution 當為 true 時，陣列會以包含元素（頁面、欄、儲存格等）的最大寬度進行間距配置。 |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution 當為 true 時，陣列的內容會以陣列物件的最大寬度進行間距配置。 |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution 當為 true 時，陣列的內容會以陣列物件的最大寬度進行間距配置。 |
| [getRowSpacingRule()](#getRowSpacingRule--) | 陣列元素之間的垂直間距類型 |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 陣列元素之間的垂直間距類型 |
| [getRowSpacing()](#getRowSpacing--) | 陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用，若為 Exactly，度量單位為點；若為 Multiple，度量單位為半行。 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用，若為 Exactly，度量單位為點；若為 Multiple，度量單位為半行。 |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


陣列的項目集合

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**返回：**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```


指定陣列相對於周圍文字的對齊方式。陣列外的文字可與陣列物件的底部、頂部或中心對齊。預設值: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**返回：**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```


指定陣列相對於周圍文字的對齊方式。陣列外的文字可與陣列物件的底部、頂部或中心對齊。預設值: Center

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
public abstract boolean getMaximumDistribution()
```


Maximum Distribution 當為 true 時，陣列會以包含元素（頁面、欄、儲存格等）的最大寬度進行間距配置。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**返回：**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```


Maximum Distribution 當為 true 時，陣列會以包含元素（頁面、欄、儲存格等）的最大寬度進行間距配置。

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
public abstract boolean getObjectDistribution()
```


Object Distribution 當為 true 時，陣列的內容會以陣列物件的最大寬度進行間距配置。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**返回：**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```


Object Distribution 當為 true 時，陣列的內容會以陣列物件的最大寬度進行間距配置。

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
public abstract int getRowSpacingRule()
```


陣列元素之間的垂直間距類型

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**返回：**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```


陣列元素之間的垂直間距類型

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
public abstract long getRowSpacing()
```


陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用，若為 Exactly，度量單位為點；若為 Multiple，度量單位為半行。預設: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**返回：**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```


陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用，若為 Exactly，度量單位為點；若為 Multiple，度量單位為半行。預設: 0

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